Euler-Mascheroni Constant
===
[![NPM version][npm-image]][npm-url] [![Build Status][build-image]][build-url] [![Coverage Status][coverage-image]][coverage-url] [![Dependencies][dependencies-image]][dependencies-url]

> The [Euler-Mascheroni][eulergamma] constant.

The [Euler-Mascheroni][eulergamma] constant `gamma` (also known as "Euler's constant" or "the Euler constant") is defined as the limit of the sequence

<div class="equation" align="center" data-raw-text="\gamma = \lim_{n\to\infty} \left( \sum_{k=1}^n \frac{1}{k} - \ln n \right)" data-equation="eq:const_eulergamma">
	<img src="https://cdn.rawgit.com/const-io/eulergamma/03a49a9a31f1b486b6146864622113811f48d56a/docs/img/eqn.svg" alt="Equation for the Euler-Mascheroni constant.">
	<br>
</div>


## Installation

``` bash
$ npm install const-eulergamma
```


## Usage

``` javascript
var GAMMA = require( 'const-eulergamma' );
```

#### GAMMA

The [Euler-Mascheroni][eulergamma] constant.

``` javascript
GAMMA === 0.5772156649015329;
```


## Examples

``` javascript
var GAMMA = require( 'const-eulergamma' );

console.log( GAMMA );
// returns 0.5772156649015329
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


---
## Tests

### Unit

This repository uses [tape][tape] for unit tests. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul][istanbul] as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


### Browser Support

This repository uses [Testling][testling] for browser testing. To run the tests in a (headless) local web browser, execute the following command in the top-level application directory:

``` bash
$ make test-browsers
```

To view the tests in a local web browser,

``` bash
$ make view-browser-tests
```

<!-- [![browser support][browsers-image]][browsers-url] -->


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015-2016. The [Compute.io][compute-io] Authors.


[npm-image]: http://img.shields.io/npm/v/const-eulergamma.svg
[npm-url]: https://npmjs.org/package/const-eulergamma

[build-image]: http://img.shields.io/travis/const-io/eulergamma/master.svg
[build-url]: https://travis-ci.org/const-io/eulergamma

[coverage-image]: https://img.shields.io/codecov/c/github/const-io/eulergamma/master.svg
[coverage-url]: https://codecov.io/github/const-io/eulergamma?branch=master

[dependencies-image]: http://img.shields.io/david/const-io/eulergamma.svg
[dependencies-url]: https://david-dm.org/const-io/eulergamma

[dev-dependencies-image]: http://img.shields.io/david/dev/const-io/eulergamma.svg
[dev-dependencies-url]: https://david-dm.org/dev/const-io/eulergamma

[github-issues-image]: http://img.shields.io/github/issues/const-io/eulergamma.svg
[github-issues-url]: https://github.com/const-io/eulergamma/issues

[tape]: https://github.com/substack/tape
[istanbul]: https://github.com/gotwarlost/istanbul
[testling]: https://ci.testling.com

[eulergamma]: http://mathworld.wolfram.com/Euler-MascheroniConstant.html
[compute-io]: https://github.com/compute-io
