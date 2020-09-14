> - This repo is **no longer maintained**.
> - It has been superceded by [this repo](https://github.com/basher/parcel-boilerplate-storybook).

# Use Parcel to bundle UI

## Boilerplate setup.

Using Parcel bundler (instead of Webpack or Gulp) to handle

* ES6+ transpilation.
* Sass.
* PostCSS.

Additionally, configured

* IE11 ponyfill for CSS variables.
* ESLint, Stylelint, Prettier.
* Git hooks.

> Notes:
> * Linter config files use recommended settings, plus some additional personal (opinionated) settings - e.g. `eslint-config-airbnb-base`.
> * This repo is setup for raw JavaScript only - i.e. not TypeScript, or React/Angular/Vue.

## Test in browser

* `npm start` launches test page in browser.
* `npm build` creates minified static assets with map files in `dist` folder.
