# vue-mix-bootstrap

A simple Vue 2.0 app skeleton, for quick prototyping with Bootstrap 4, and easier-to-configure webpack with [Laravel Mix](https://github.com/JeffreyWay/laravel-mix). Also includes a minimal [router](https://router.vuejs.org).

## Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli).

``` bash
$ npm install -g vue-cli
$ vue init withfatpanda/vue-mix-bootstrap my-project
$ cd my-project
$ npm install
$ npm run dev
```

## What's Included

### Build Scripts

``` bash
# install dependencies
npm install
# build for production with minification
npm run production
# or build for dev
npm run dev
# or build and then watch source files and rebuild on changes
npm run watch
```

Configure your build in `./webpack.mix.js`.

### Bootstrap + FontAwesome

Create beautiful, usable things.

The stylesheets are loaded in `./src/sass/style.scss`.

Override Bootstrap's variables in `./src/sass/_variables.scss`.

### Routing

Build and amazing single-page app with friendly URLs, thanks to [Vue Router](https://router.vuejs.org).

Your routes are in `./src/js/.routes.js`.

The router is in `./src/js/main.js`.

### Linting

Linting keeps your code clean. 

Configure it in `./eslintrc.js`. 

Disable it by commenting out this section of `./webpack.mix.js`:

```js
rules: [
  {
    test: /\.(js|vue)$/,
    loader: 'eslint-loader',
    enforce: 'pre',
    include: [src],
    options: {
      formatter: require('eslint-friendly-formatter')
    }
  }
]
```

## Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/vue-mix-bootstrap my-project
```
