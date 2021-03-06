# markdown-it-checkbox [![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url] [![devDependency Status][devdepstat-image]][devdepstat-url]

> Plugin to create checkboxes for [markdown-it](https://github.com/markdown-it/markdown-it) markdown parser.

This plugin allows to create checkboxes for tasklists as discussed [here](http://talk.commonmark.org/t/task-lists-in-standard-markdown/41).



## Usage

## Install

node.js, browser:

```bash
npm install markdown-it-checkbox --save
bower install markdown-it-checkbox --save
```

## Use

```js
var md = require('markdown-it')()
            .use(require('markdown-it-checkbox'));

md.render('[ ] unchecked') // =>
// <p>
//  <input type="checkbox" id="checkbox0">
//  <label for="checkbox0">unchecked</label>
// </p>
```

_Differences in browser._ If you load script directly into the page, without
package system, module will add itself globally as `window.markdownitCheckbox`.


## License


## License

[MIT License](https://github.com/mcecot/markdown-it-checkbox/blob/master/LICENSE) © 2015 Markus Cecot

[npm-url]: https://npmjs.org/package/markdown-it-checkbox
[npm-image]: https://img.shields.io/npm/v/markdown-it-checkbox.svg

[travis-url]: http://travis-ci.org/mcecot/markdown-it-checkbox
[travis-image]: https://secure.travis-ci.org/mcecot/markdown-it-checkbox.svg?branch=master

[coveralls-url]: https://coveralls.io/r/mcecot/markdown-it-checkbox
[coveralls-image]: https://img.shields.io/coveralls/mcecot/markdown-it-checkbox.svg

[depstat-url]: https://david-dm.org/mcecot/markdown-it-checkbox
[depstat-image]: https://david-dm.org/mcecot/markdown-it-checkbox.svg

[devdepstat-url]: https://david-dm.org/mcecot/markdown-it-checkbox#info=devDependencies
[devdepstat-image]: https://david-dm.org/mcecot/markdown-it-checkbox/dev-status.svg
