# @devtea2027/beatae-enim-repellendus-sint <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @devtea2027/beatae-enim-repellendus-sint
```

## Usage/Examples

```js
var regexTester = require('@devtea2027/beatae-enim-repellendus-sint');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2027/beatae-enim-repellendus-sint
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2027/beatae-enim-repellendus-sint.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2027/beatae-enim-repellendus-sint.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2027/beatae-enim-repellendus-sint
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2027/beatae-enim-repellendus-sint/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2027/beatae-enim-repellendus-sint#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2027/beatae-enim-repellendus-sint.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2027/beatae-enim-repellendus-sint.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2027/beatae-enim-repellendus-sint.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2027/beatae-enim-repellendus-sint
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2027/beatae-enim-repellendus-sint/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2027/beatae-enim-repellendus-sint/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2027/beatae-enim-repellendus-sint
[actions-url]: https://github.com/devtea2027/beatae-enim-repellendus-sint/actions
