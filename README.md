# Number.isInteger <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Number.isInteger` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@taktikorg/aut-optio).

## Getting started

```sh
npm install --save @taktikorg/aut-optio
```

## Usage/Examples

```js
console.log(Number.isInteger(-3)); // true
console.log(Number.isInteger(2 ** 54)); // true
console.log(Number.isInteger(2.3)); // false
console.log(Number.isInteger(Infinity)); // false
console.log(Number.isInteger("7")); // false
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/aut-optio
[npm-version-svg]: https://versionbadg.es/taktikorg/aut-optio.svg
[deps-svg]: https://david-dm.org/taktikorg/aut-optio.svg
[deps-url]: https://david-dm.org/taktikorg/aut-optio
[dev-deps-svg]: https://david-dm.org/taktikorg/aut-optio/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikorg/aut-optio#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/aut-optio.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/aut-optio.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/aut-optio.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/aut-optio
[codecov-image]: https://codecov.io/gh/taktikorg/aut-optio/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikorg/aut-optio/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikorg/aut-optio
[actions-url]: https://github.com/taktikorg/aut-optio/actions
