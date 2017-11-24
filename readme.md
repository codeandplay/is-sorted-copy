# is-sorted-copy
### This is clone of https://github.com/dcousens/is-sorted The purpose of the repo is just for studying
[![TRAVIS](https://secure.travis-ci.org/codeandplay/is-sorted-copy.png)](http://travis-ci.org/codeandplay/is-sorted-copy)
[![NPM](https://img.shields.io/npm/v/is-sorted.svg)](https://www.npmjs.org/package/is-sorted)
[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

A small module to check if an Array is sorted.

## Example
``` javascript
var sorted = require('is-sorted')
console.log([1, 2, 3]);
/// => true

console.log(sorted([3, 1, 2]))
// => false

// supports custom comparators
console.log(sorted([3, 2, 1], function (a, b) {return b - a})
// => true
```

## LICENSE [MIT] (LICENSE)