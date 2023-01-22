## Day 12/100

---

Date: 18/01/23

---

### Goal: 

Make a simple portfolio + blog site using SvelteKit for my anon account

### **Today's Progress**: 

- Made a decision on how to handle data: git submodules and dynamic imports
- Adds 100days-of-code repo as a git submodule, so we now clone that data into this repo
- Adds load function that uses import.meta.glob to try to import the files from the submodule
- Adds parsing of this import queue to get the files that are trying to be imported
- Uses the file names for the /blog list
- Bunch of testing for the location of this new submodule
- Removes a lot of store and fetch code implementations

### **Thoughts**: 
- Seems a lot cleaner to go down this way and allows for easier parsing of the content in the files too

### **Link to work:** 
- [Portfolio - Repo](https://github.com/activate-glacier-instinct/activate-glacier-instinct.github.io)
- [Portfolio - Deployment](https://activate-glacier-instinct.github.io/)
- [Portfolio - Design Moodboard](https://www.figma.com/file/EACX3PwCLrEc2q3oHRtxU4/Portfolio---Moodboard?node-id=0%3A1)