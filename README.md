# @zitterorg/unde-exercitationem <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Determine whether the environment has the so-called "override mistake" - [[Set]]ing a property whose ancestor is nonwritable throws.

## Example

```js
var hasOverrideMistake = require('@zitterorg/unde-exercitationem');
var assert = require('assert');

assert.equal(typeof hasOverrideMistake(), 'boolean', 'returns true or false');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/unde-exercitationem
[npm-version-svg]: https://versionbadg.es/inspect-js/@zitterorg/unde-exercitationem.svg
[deps-svg]: https://david-dm.org/inspect-js/@zitterorg/unde-exercitationem.svg
[deps-url]: https://david-dm.org/inspect-js/@zitterorg/unde-exercitationem
[dev-deps-svg]: https://david-dm.org/inspect-js/@zitterorg/unde-exercitationem/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@zitterorg/unde-exercitationem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/unde-exercitationem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/unde-exercitationem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/unde-exercitationem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/unde-exercitationem
[codecov-image]: https://codecov.io/gh/inspect-js/@zitterorg/unde-exercitationem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@zitterorg/unde-exercitationem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@zitterorg/unde-exercitationem
[actions-url]: https://github.com/zitterorg/unde-exercitationem/actions
