## Day 15/100

---

Date: 21/01/23

---

### Goal: 

Make a simple portfolio + blog site using SvelteKit for my anon account

### **Today's Progress**: 

- Content: normalises the style across all notes and updates the submodule in the portfolio repo
- Moved the 100days-of-code summary page to be within /blog
- Adds ability for /blog to read from a new content/blog/page.json data. Enables the ability to write blogs and showcase the links directly on the /blog page
- Fix: pages nested within /blog/100days-of-code could not be rendered because of a missing /
- Moved all the links to logs to the 100days-of-code page. Old `/blog/[slug]` was moved here
- Updates the 100days-of-code nested pages data generation and link building
- Tested navigation throughout the app: home -> blog/100days-of-code -> blog/100days-of-code/[slug] and home -> /blog -> blog/100days-of-code  

### **Thoughts**: 
- Felt quite nice to fix the navigation to follow a logical flow

### **Next**:
- Style `/blog/[slug]`

### **Link to work:** 
- [Portfolio - Repo](https://github.com/activate-glacier-instinct/activate-glacier-instinct.github.io)
- [Portfolio - Deployment](https://activate-glacier-instinct.github.io/)
- [Portfolio - Design Moodboard](https://www.figma.com/file/EACX3PwCLrEc2q3oHRtxU4/Portfolio---Moodboard?node-id=0%3A1)