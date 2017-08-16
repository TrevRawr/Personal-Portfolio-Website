# Personal Portfolio Website

## About

This repository hosts the source code for my personal portfolio website. To see the deployed website, [click here](https://trevrawr.github.io/). The website is deployed using GitHub Pages in a [separate repository (https://github.com/TrevRawr/TrevRawr.github.io). This was done so the site could be deployed as a "User" GitHub Pages website. see the README in the GitHub Pages repository for a more detailed explanation.

## Tools Used

This site was built with [Vue.js](https://vuejs.org/) and [Vuetify](https://vuetifyjs.com/). The project is structured around the default [Vue.js cli webpack boilerplate](https://github.com/vuejs-templates/webpack), which uses Node Package Manager (NPM) and Webpack for deployment. In addition to the NPM packages included with the boilerplate, I have added [vue-gh-pages](https://www.npmjs.com/package/vue-gh-pages) for helping with deployment to GitHub Pages, and [prerender-spa-plugin](https://www.npmjs.com/package/prerender-spa-plugin) for Search Engine Optimization.

## Build Setup

Make sure you have [NPM](https://nodejs.org/en/download/) installed.

``` bash
# install dependencies. Do this before executing any of the below commands
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for GitHub pages in a separate docs folder
npm run deploy

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
