# webpack-library-starter

Repository contains a template for building a JavaSCript library that can be imported into any application. The template is uses webpack to convert ES6 to universal JavaScript. The template was originally created by Krasimir Tsonev and can be found here: https://github.com/krasimir/webpack-library-starter. I am hosting this template on my GitHub so that I may modify it for my own needs.

## Getting Started

These instructions will get your copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Software you'll need to run the project

```
An IDE
npm or yarn
```

### Installing

A step by step series of examples that tell you how to get a development env running

```
git clone https://github.com/jasonrberney/webpack-library-starter
cd webpack-library-starter
yarn install
Open `webpack.config.js` file and change the value of `libraryName` variable.
Open `package.json` file and change the value of `main` property so it matches the name of your library.
yarn build
```

## Commands

* `yarn build` or `npm run build` - produces production version of your library under the `lib` folder
* `yarn dev` or `npm run dev` - produces development version of your library and runs a watcher
* `yarn test` or `npm run test` - well ... it runs the tests :)
* `yarn test:watch` or `npm run test:watch` - same as above but in a watch mode

## Built With

* [webpack](https://webpack.js.org/) - The JavaScript bundler
* [Yarn](https://yarnpkg.com/en/) - The package manager used

## Authors

* **Krasimir Tsonev**
* **Jason Berney**
