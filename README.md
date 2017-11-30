# 2017-09-14 jsy-react-semantic-rollup

Pursing control and small javascript bundle sizes using
my current favorite technologies:

  - Frontend :
    - [rollup](https://rollupjs.org)
    - [babel-preset-jsy](https://github.com/shanewholloway/babel-preset-jsy) / [babel-plugin-offside-js](https://github.com/shanewholloway/babel-plugin-offside-js)
    - [semantic-ui](https://semantic-ui.com) and [react.semantic-ui.com](https://react.semantic-ui.com)
    - [react](https://facebook.github.io/react) or [preact](https://preactjs.com)

  - Backend :
    - [node 8.5](https://nodejs.org)
    - [express 4](http://expressjs.com)

## Installing

```bash
$ git clone git@github.com:shanewholloway/2017-09-14-jsy-react-semantic-rollup.git
$ cd 2017-09-14-jsy-react-semantic-rollup
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

