# @emiplegiaqmnpm/recusandae-tenetur-sequi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@emiplegiaqmnpm/recusandae-tenetur-sequi');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/recusandae-tenetur-sequi
[npm-version-svg]: https://versionbadg.es/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi.svg
[deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi.svg
[deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi
[dev-deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/recusandae-tenetur-sequi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/recusandae-tenetur-sequi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/recusandae-tenetur-sequi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/recusandae-tenetur-sequi
[codecov-image]: https://codecov.io/gh/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@emiplegiaqmnpm/recusandae-tenetur-sequi
[actions-url]: https://github.com/emiplegiaqmnpm/recusandae-tenetur-sequi/actions
