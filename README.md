# @hishprorg/corrupti-vero <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @hishprorg/corrupti-vero
```

## Usage/Examples

```js
var regexTester = require('@hishprorg/corrupti-vero');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hishprorg/corrupti-vero
[npm-version-svg]: https://versionbadg.es/ljharb/@hishprorg/corrupti-vero.svg
[deps-svg]: https://david-dm.org/ljharb/@hishprorg/corrupti-vero.svg
[deps-url]: https://david-dm.org/ljharb/@hishprorg/corrupti-vero
[dev-deps-svg]: https://david-dm.org/ljharb/@hishprorg/corrupti-vero/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishprorg/corrupti-vero#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishprorg/corrupti-vero.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/corrupti-vero.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/corrupti-vero.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/corrupti-vero
[codecov-image]: https://codecov.io/gh/ljharb/@hishprorg/corrupti-vero/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishprorg/corrupti-vero/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishprorg/corrupti-vero
[actions-url]: https://github.com/hishprorg/corrupti-vero/actions
