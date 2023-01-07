# 100 Days Of Code - Log

================

## Day 1

Date: 07/01/23

================

> Goal: make a simple portfolio + blog site using SvelteKit for my anon account

### **Today's Progress**: 

- build was quite easy, just followed the docs 
        - https://kit.svelte.dev/docs/creating-a-project
    - changes the main page html, but missing a style
    - started looking at CI/CD using Github Actions
        - first need to build to static using an [adapter-static]
(https://www.npmjs.com/package/@sveltejs/adapter-static)
        - Svelte also has an [adapter-auto](https://www.npmjs.com/package/@sveltejs/adapter-auto)
            - added setup by following the module docs
            - getting an error about not all routes being prerendered
    - added a Github Action to build and deploy the site
        - currently not showing anything
            - probably relate to the above
            - also there's no index.html in the /out folder
            ![](/assets/images/2023-01-07-17-49-23.png)

### **Thoughts:**: 

- Cloudflare Pages deployment works by default, worth a try
- SvelteKit seems really nice 
    - Super fast to build
    - The deployment Github Action I used was from a static Next.js build and worked just fine
- Playwright tests are very nice
- /out folder is 93kb, love that I can build this precompressed with brotli and gzip
- Glad that I spent some time to make a bash script that allows me to configure the repos with my anon credentials
    - need to look at a VM in the future
- Used the Github Projects view a lot 
    - very, very nice to use as a board and as a spreadsheet
- Also using a proper flow
    - Issues --> Branches --> PRs

### **Link to work:** 
- [Portfolio - activate-glacier-instinct](https://github.com/activate-glacier-instinct/activate-glacier-instinct.github.io)



