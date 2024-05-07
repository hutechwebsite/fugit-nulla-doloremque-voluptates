# Math.f16round <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ES-spec-compliant `Math.f16round` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @hutechwebsite/fugit-nulla-doloremque-voluptates
```

## Usage/Examples

```js
const f16round = require('@hutechwebsite/fugit-nulla-doloremque-voluptates');
const assert = require('assert');

assert.equal(f16round(42.84), 42.84375);
assert.equal(f16round(0.123), 0.12298583984375);
assert.equal(f16round(-0.123), -0.12298583984375);
assert.equal(f16round(1.337), 1.3369140625);
assert.equal(f16round(65504), 65504);
assert.equal(f16round(65505), 65504);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@hutechwebsite/fugit-nulla-doloremque-voluptates
[npm-version-svg]: https://versionbadg.es/hutechwebsite/fugit-nulla-doloremque-voluptates.svg
[deps-svg]: https://david-dm.org/hutechwebsite/fugit-nulla-doloremque-voluptates.svg
[deps-url]: https://david-dm.org/hutechwebsite/fugit-nulla-doloremque-voluptates
[dev-deps-svg]: https://david-dm.org/hutechwebsite/fugit-nulla-doloremque-voluptates/dev-status.svg
[dev-deps-url]: https://david-dm.org/hutechwebsite/fugit-nulla-doloremque-voluptates#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hutechwebsite/fugit-nulla-doloremque-voluptates.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hutechwebsite/fugit-nulla-doloremque-voluptates.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hutechwebsite/fugit-nulla-doloremque-voluptates.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hutechwebsite/fugit-nulla-doloremque-voluptates
[codecov-image]: https://codecov.io/gh/hutechwebsite/fugit-nulla-doloremque-voluptates/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/hutechwebsite/fugit-nulla-doloremque-voluptates/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/hutechwebsite/fugit-nulla-doloremque-voluptates
[actions-url]: https://github.com/hutechwebsite/fugit-nulla-doloremque-voluptates/actions
