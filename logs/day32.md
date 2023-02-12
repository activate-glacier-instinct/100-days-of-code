## Day 32/100

---

Date: 12/02/23

---

### Goal: 

Build a full NFT collection smart contract in Foundry - LW3 Sophomore track

### **Today's Progress**: 

- Foundry: learned more about fuzzing and warping
- Contract: added `init()` contract tests, learned about [makeAddr](https://book.getfoundry.sh/reference/forge-std/make-addr?highlight=makeAddr#makeaddr) Foundry util
- Contract: added a variety of success and fail tests for the `mint()` method
- Contract: test coverage at 22%
- Foundry: learned about editing the block times and using [warp](https://book.getfoundry.sh/cheatcodes/warp)


### **Thoughts**: 

- The fact that I'm using an interface contract for the Whitelist confused me a bit. I needed to include this interface in the tests, but how could I pass in an `address` type when all I had was a string.
- Resources and videos from [thirdweb](https://www.youtube.com/@thirdweb_) on Foundry have been incredible. 
- Finish the [Patrick Collins video on Foundry](https://www.youtube.com/watch?v=fNMfMxGxeag), but I found it to skip over a lot of interesting things. Needs to spend more time combing through [his recommended repo](https://github.com/PatrickAlphaC/foundry-play). 

### **Link to work:** 
- [NFT Collection (contract) - Project Repo](https://github.com/activate-glacier-instinct/nft-collection-contract-foundry--lw3)
- [My Portfolio](https://activate-glacier-instinct.github.io/)