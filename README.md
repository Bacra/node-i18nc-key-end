I18NC-KEY-END
==================


[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls][coveralls-image]][coveralls-url]
[![NPM License][license-image]][npm-url]

# Install

```
npm install i18nc i18nc-key-end --save
```

# Useage

```javascript
var i18nc = require('i18nc');
require('i18nc-key-end')(i18nc);

var info = i18nc('var str="你好！需要帮忙吗？"', {pluginEnabled: {keyEnd: true}});
console.log(info.code);	// var str=I18N('你好！')+I18N('需要帮忙吗？');
```


[npm-image]: http://img.shields.io/npm/v/i18nc-key-end.svg
[downloads-image]: http://img.shields.io/npm/dm/i18nc-key-end.svg
[npm-url]: https://www.npmjs.org/package/i18nc-key-end
[travis-image]: http://img.shields.io/travis/Bacra/node-i18nc-key-end/master.svg?label=linux
[travis-url]: https://travis-ci.org/Bacra/node-i18nc-key-end
[coveralls-image]: https://img.shields.io/coveralls/Bacra/node-i18nc-key-end.svg
[coveralls-url]: https://coveralls.io/github/Bacra/node-i18nc-key-end
[license-image]: http://img.shields.io/npm/l/i18nc-key-end.svg
