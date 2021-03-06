# Vue 3 + Vite + GSAP + SASS

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

&nbsp;
&nbsp;
# Demo POC (Proof of concept)
### Author: Fabio Politi (f.politi@icoa.it)
&nbsp;
## How to use (development)
- clone this repo
- run `npm install`
- run 'npm run dev'
- open the app at [localhost:3000](http://localhost:3000)

&nbsp;
## How to use (production) - (Local: TBC)
- find out the "relative base public path", such as "/static/gsap-demo/"
- run `npx vite build --base=[BASE PATH HERE]`, such as `npx vite build --base=/static/gsap-demo/`
- all the assets and the articats will be generated into the "dist" folder
- transfer all the content of the "dist" folder to the production server (TBC)
- open the file at "dist/index.html", copy the CSS/JS declaration and inject them into another website
- place the markup `<div id="app"></div>` into a CMS page of the outher website

&nbsp;
## How to use (production) - (Vercel)
### Vercel for Git
- Push your code to your git repository (GitHub, GitLab, Bitbucket).
- [Import your Vite project](https://vercel.com/new) into Vercel.
- Vercel will detect that you are using Vite and will enable the correct settings for your deployment.
- Your application is deployed! (e.g. [vite-vue-gsap-sass-poc.vercel.app](https://vite-vue-gsap-sass-poc.vercel.app/))

After your project has been imported and deployed, all subsequent pushes to branches will generate Preview Deployments, and all changes made to the Production Branch (commonly “main”) will result in a Production Deployment.

Learn more about Vercel’s [Git Integration](https://vercel.com/docs/concepts/git).
