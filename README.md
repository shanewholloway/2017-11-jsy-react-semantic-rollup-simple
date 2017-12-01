# 2017-11 jsy-react-semantic-rollup-simple 

Pursing control and small javascript bundle sizes using
my current favorite technologies:

  - Frontend :
    - [rollup](https://rollupjs.org)
    - [babel-preset-jsy](https://github.com/shanewholloway/babel-preset-jsy) / [babel-plugin-offside-js](https://github.com/shanewholloway/babel-plugin-offside-js)
    - [semantic-ui](https://semantic-ui.com) and [react.semantic-ui.com](https://react.semantic-ui.com)
    - [react](https://facebook.github.io/react) or [preact](https://preactjs.com)
    - [fela](http://fela.js.org/) with [react-fela](http://fela.js.org/docs/guides/UsageWithReact.html)
    - [polished](https://polished.js.org/)

  - Backend :
    - [node 8.9](https://nodejs.org)
    - [express 4](http://expressjs.com)

## Installing

```bash
$ git clone git@github.com:shanewholloway/2017-11-jsy-react-semantic-rollup-simple.git
$ cd 2017-11-jsy-react-semantic-rollup-simple
$ npm install .
$ npm run build  # or npm run watch
$ npm run start
```

Then open in browser.


## Bundle Sizes and Performance

Take a look at the network inspector under your browser's devtools. Also take a look at the resulting file sizes: 

```bash
$ wc -c ./dist/public/*.min.js.gz ./dist/public/css/*.min.css.gz

   31983 ./dist/public/main.min.js.gz
    7212 ./dist/public/vendor.min.js.gz
   59953 ./dist/public/css/semantic.min.css.gz
   99148 total
```

## License

[BSD-2-Clause](LICENSE)

