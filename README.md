## Versions
 - Hugo `0.62.2`
 - Bootstrap `4.4.1`
 - Node.js `12.14.0`

## CI/CD
![ci-cd-master](https://github.com/inwardmovement/mettaconseilpro/workflows/ci-cd-master/badge.svg?branch=master)

## To develop locally
- Install the corresponding version of [Hugo](https://gohugo.io/)
- Install the corresponding version of [Node.js via nvm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
  - On Windows:
    - Install [nvm-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades)
    - Run `nvm install [Node.js version]` (in an Admin shell)
    - Run `nvm use [Node.js version]` (in an Admin shell)
  - On OSX and Linux:
    - Install [nvm](https://github.com/nvm-sh/nvm#installation-and-update)
    - Run `nvm install [Node.js version]`
    - Run `nvm use [Node.js version]`
- Install dependencies: `npm i`
- Install [Netlify CLI](https://docs.netlify.com/cli/get-started/), [gulp-cli](https://www.npmjs.com/package/gulp-cli), [PostCSS CLI](https://github.com/postcss/postcss-cli) and [Autoprefixer](https://github.com/postcss/autoprefixer) globally: `npm i -g netlify-cli gulp-cli postcss-cli autoprefixer`
- Clone the repo and run `npm start` from root
