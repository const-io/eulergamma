Euler-Mascheroni Constant
===
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependencies][dependencies-image]][dependencies-url]

> The [Euler-Mascheroni](http://mathworld.wolfram.com/Euler-MascheroniConstant.html) constant.

The Euler-Mascheroni constant `gamma` (also known as "Euler's constant" or "the Euler constant") is defined as the limit of the sequence


<div class="equation" align="center" data-raw-text="\gamma = \lim_{n\to\infty} \left( \sum_{k=1}^n \frac{1}{k} - \ln n \right)" data-equation="eq:const_eulergamma">
	<img src="https://cdn.rawgit.com/compute-io/const-eulergamma/03a49a9a31f1b486b6146864622113811f48d56a/docs/img/eqn.svg" alt="Equation for the Euler-Mascheroni constant.">
	<br>
</div>



## Installation

``` bash
$ npm install compute-const-eulergamma
```

For use in the browser, use [browserify](https://github.com/substack/node-browserify).


## Usage

``` javascript
var gamma = require( 'compute-const-eulergamma' );
```

#### gamma

The [Euler-Mascheroni](http://mathworld.wolfram.com/Euler-MascheroniConstant.html) constant.

``` javascript
gamma === 0.5772156649015329;
```


## Examples

``` javascript
var gamma = require( 'compute-const-eulergamma' );

console.log( gamma );
// returns 0.5772156649015329
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


## Tests

### Unit

Unit tests use the [Mocha](http://mochajs.org/) test framework with [Chai](http://chaijs.com) assertions. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul](https://github.com/gotwarlost/istanbul) as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


---
## License

[MIT license](http://opensource.org/licenses/MIT).


## Copyright

Copyright &copy; 2015. Athan Reines.


[npm-image]: http://img.shields.io/npm/v/compute-const-eulergamma.svg
[npm-url]: https://npmjs.org/package/compute-const-eulergamma

[travis-image]: http://img.shields.io/travis/compute-io/const-eulergamma/master.svg
[travis-url]: https://travis-ci.org/compute-io/const-eulergamma

[coveralls-image]: https://img.shields.io/coveralls/compute-io/const-eulergamma/master.svg
[coveralls-url]: https://coveralls.io/r/compute-io/const-eulergamma?branch=master

[dependencies-image]: http://img.shields.io/david/compute-io/const-eulergamma.svg
[dependencies-url]: https://david-dm.org/compute-io/const-eulergamma

[dev-dependencies-image]: http://img.shields.io/david/dev/compute-io/const-eulergamma.svg
[dev-dependencies-url]: https://david-dm.org/dev/compute-io/const-eulergamma

[github-issues-image]: http://img.shields.io/github/issues/compute-io/const-eulergamma.svg
[github-issues-url]: https://github.com/compute-io/const-eulergamma/issues
