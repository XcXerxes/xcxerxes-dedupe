# xcxerxes-array-last [![NPM version](https://img.shields.io/npm/v/xcxerxes-dedupe.svg)](https://www.npmjs.com/package/xcxerxes-dedupe) [![Build Status](https://travis-ci.org/XcXerxes/xcxerxes-dedupe.svg)](https://travis-ci.org/XcXerxes/xcxerxes-dedupe.svg)

remove duplicates elem

## Example

```javascript
var deduped = require('xcxerxes-dedupe')
console.log(deduped([1, 2, 3, 4, 4, 5]))
// -> [1, 2, 3, 4, 5]

console.log(deduped([1, 1, 1, 2, 3, 4, 4, 5, 1, 1]))
// -> [1, 2, 3, 4, 5]

console.log(deduped([{a: 1}, {a: 2}, {a: 3}, {a: 3}]))
// -> [{a: 1}, {a: 2}, {a: 3}]

console.log(deduped([{a: 1, b: 1}, {a: 2, b: 2}, {a: 3, b: 3}, {a: 3, b: 4}]))
// -> [{a: 1, b: 1}, {a: 2, b: 2}, {a: 3, b: 3}]

```
## License
Copyright © 2018 [xcxerxes](https://github.com/XcXerxes)
Released under the MIT license
