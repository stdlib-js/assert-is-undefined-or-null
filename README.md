<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isUndefinedOrNull

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a value is undefined or null.

<section class="installation">

## Installation

```bash
npm install @stdlib/assert-is-undefined-or-null
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var isUndefinedOrNull = require( '@stdlib/assert-is-undefined-or-null' );
```

#### isUndefinedOrNull( value )

Tests if a `value` is `undefined` or `null`.

<!-- eslint-disable no-undefined -->

```javascript
var bool = isUndefinedOrNull( undefined );
// returns true

bool = isUndefinedOrNull( null );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint-disable no-undefined, no-restricted-syntax, no-empty-function -->

<!-- eslint no-undef: "error" -->

```javascript
var isUndefinedOrNull = require( '@stdlib/assert-is-undefined-or-null' );

var bool;
var x;

bool = isUndefinedOrNull( x );
// returns true

bool = isUndefinedOrNull( undefined );
// returns true

bool = isUndefinedOrNull( void 0 );
// returns true

bool = isUndefinedOrNull( null );
// returns true

bool = isUndefinedOrNull( 'beep' );
// returns false

bool = isUndefinedOrNull( 5 );
// returns false

bool = isUndefinedOrNull( true );
// returns false

bool = isUndefinedOrNull( {} );
// returns false

bool = isUndefinedOrNull( [] );
// returns false

bool = isUndefinedOrNull( function foo() {} );
// returns false
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/assert/is-null`][@stdlib/assert/is-null]</span><span class="delimiter">: </span><span class="description">test if a value is null.</span>
-   <span class="package-name">[`@stdlib/assert/is-undefined`][@stdlib/assert/is-undefined]</span><span class="delimiter">: </span><span class="description">test if a value is undefined.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-undefined-or-null.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-undefined-or-null

[test-image]: https://github.com/stdlib-js/assert-is-undefined-or-null/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-is-undefined-or-null/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-undefined-or-null/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-undefined-or-null?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-undefined-or-null.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-undefined-or-null/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-is-undefined-or-null/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-is-undefined-or-null/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-is-undefined-or-null/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-is-undefined-or-null/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-undefined-or-null/main/LICENSE

<!-- <related-links> -->

[@stdlib/assert/is-null]: https://github.com/stdlib-js/assert-is-null

[@stdlib/assert/is-undefined]: https://github.com/stdlib-js/assert-is-undefined

<!-- </related-links> -->

</section>

<!-- /.links -->
