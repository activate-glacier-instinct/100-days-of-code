## Day 11

Date: 17/01/23

================

> Goal: make a simple portfolio + blog site using SvelteKit for my anon account

### **Today's Progress**: 

- Added a /lib folder and moved a bunch of utilities there
- Added a store for fetched posts from Github 
- Rendered the data from this new store on the /blog page
- Stopped the /blog/[slug] from making too many calls onLoad (pre-rendering on hover)
- Simplified the blog/+layout by removing both loading logic and data definitions

### **Thoughts**: 
- Tricky to think about this problem: fetch list data when hitting /blog, but then when you render /blog/[slug] render the individual item from the list
- Some avenues:
    - Service workers downloading the files locally, then the app uses these files to push .md contents into html
    - Dynamically fetch the data on /blog, reuse it on /blog/[slug] using a store

### **Link to work:** 
- [Portfolio - Repo](https://github.com/activate-glacier-instinct/activate-glacier-instinct.github.io)
- [Portfolio - Deployment](https://activate-glacier-instinct.github.io/)
- [Portfolio - Design Moodboard](https://www.figma.com/file/EACX3PwCLrEc2q3oHRtxU4/Portfolio---Moodboard?node-id=0%3A1)