# vue-framework7-webpack-template

> A simple template to get started with VueJS + Framework7 + Webpack.

> This template only works for Vue 2.0. Older versions like Vue 1.x are not supported!

### Compatibility

- Framework7 v1: yes
- Framework7 v2: no
- VueJS 2.x+: yes

### Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli).

Replace ***my-project*** with the name of your project!

``` bash
$ npm install -g vue-cli
$ vue init valnub/vue-framework7-webpack-template my-project
$ cd my-project
$ npm install
$ npm run dev
```

### What's Included

- `npm run dev`: Webpack + `vue-loader` with proper config for source maps & hot-reload.
- `npm run build`: build with HTML/CSS/JS minification.
- Ready-to-use Framework7 plugin and example code

For detailed explanation on how things work:
- Check out my [video screencast](https://www.timo-ernst.net/blog/2016/11/13/how-to-get-started-with-framework7-vuejs-and-webpack).
- Consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
- Also check out the [breaking changes in vue-loader@9.0.0](https://github.com/vuejs/vue-loader/releases/tag/v9.0.0).

### Issues

If you get "undefined" in your GUI after starting the app, cd to your project folder and do this:

1. cd node_modules/framework7-vue
2. npm install
3. gulp dist

### More information

On my blog http://www.timo-ernst.net
