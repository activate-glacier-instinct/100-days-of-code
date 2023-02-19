## Day 35/100

---

Date: 18/02/23

---

### Goal: 

Build a full NFT collection smart contract in Foundry - LW3 Sophomore track

### **Today's Progress**: 

- Foundry: implemented static whitelist and nonWhitelist addresses
- Foundry: adds mint and presaleMint tests 
- Foundry: adds withdraw test
- Test coverage: 84%

### **Thoughts**:

- Attempted testing log emits from within the contract during the mint, but had errors around mismatched log signatures. Could not resolve in time for the end of this session.
- Left to test are `receive()` and `fallback()` functions
- Dug deep into the Open Zeppellin contact definitions to figure out the correct test signature
- Learned about `vm.deal()` which sends eth to an address in a test setting 
- Need to start deploying to Sepolia instead of Goerli, but its not clear if LearnWeb3 will support Sepolia

### **Next**:

- Deployment script and actual deployment to Goerli or Sepolia

### **Link to work:** 
- [NFT Collection (contract) - Project Repo](https://github.com/activate-glacier-instinct/nft-collection-contract-foundry--lw3)
- [My Portfolio](https://activate-glacier-instinct.github.io/)