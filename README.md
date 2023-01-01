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

# Anscombe's Quartet

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Anscombe's quartet][anscombes-quartet].

<section class="intro">

[Anscombe's quartet][anscombes-quartet] is a set of `4` datasets which all have nearly identical simple statistical properties but vary considerably when graphed. [Anscombe][francis-anscombe] created the datasets to demonstrate why graphical data exploration should **precede** statistical data analysis and to show the effect of outliers on statistical properties.

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/datasets-anscombes-quartet
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
var data = require( '@stdlib/datasets-anscombes-quartet' );
```

#### data()

Returns [Anscombe's quartet][anscombes-quartet], which is comprised of `4` individual datasets, where each individual dataset is an `array` of `[x,y]` tuples.

```javascript
var d = data();
/* returns
    [
        [
            [ 10, 8.04 ],
            [ 8, 6.95 ],
            [ 13, 7.58 ],
            [ 9, 8.81 ],
            [ 11, 8.33 ],
            [ 14, 9.96 ],
            [ 6, 7.24 ],
            [ 4, 4.26 ],
            [ 12, 10.84 ],
            [ 7, 4.82 ],
            [ 5, 5.68 ]
        ],
        [
            [ 10, 9.14 ],
            [ 8, 8.14 ],
            [ 13, 8.74 ],
            [ 9, 8.77 ],
            [ 11, 9.26 ],
            [ 14, 8.1 ],
            [ 6, 6.13 ],
            [ 4, 3.1 ],
            [ 12, 9.13 ],
            [ 7, 7.26 ],
            [ 5, 4.74 ]
        ],
        [
            [ 10, 7.46 ],
            [ 8, 6.77 ],
            [ 13, 12.74 ],
            [ 9, 7.11 ],
            [ 11, 7.81 ],
            [ 14, 8.84 ],
            [ 6, 6.08 ],
            [ 4, 5.39 ],
            [ 12, 8.15 ],
            [ 7, 6.42 ],
            [ 5, 5.73 ]
        ],
        [
            [ 8, 6.58 ],
            [ 8, 5.76 ],
            [ 8, 7.71 ],
            [ 8, 8.84 ],
            [ 8, 8.47 ],
            [ 8, 7.04 ],
            [ 8, 5.25 ],
            [ 19, 12.5 ],
            [ 8, 5.56 ],
            [ 8, 7.91 ],
            [ 8, 6.89 ]
        ]
    ]
*/
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: more interesting example involving stats and plotting once ndarray -->

<!-- eslint no-undef: "error" -->

```javascript
var data = require( '@stdlib/datasets-anscombes-quartet' );

console.log( data() );
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use the module as a general utility, install the module globally

```bash
npm install -g @stdlib/datasets-anscombes-quartet
```

</section>

<!-- CLI usage documentation. -->

<section class="usage">

### Usage

```text
Usage: anscombes-quartet [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="notes">

### Notes

-   Data is written to `stdout` as comma-separated values ([CSV][csv]), where the first line is a header line.

</section>

<!-- /.notes -->

<section class="examples">

### Examples

```bash
$ anscombes-quartet
x1,y1,x2,y2,x3,y3,x4,y4
10,8.04,10,9.14,10,7.46,8,6.58
8,6.95,8,8.14,8,6.77,8,5.76
13,7.58,13,8.74,13,12.74,8,7.71
9,8.81,9,8.77,9,7.11,8,8.84
11,8.33,11,9.26,11,7.81,8,8.47
14,9.96,14,8.1,14,8.84,8,7.04
6,7.24,6,6.13,6,6.08,8,5.25
4,4.26,4,3.1,4,5.39,19,12.5
12,10.84,12,9.13,12,8.15,8,5.56
7,4.82,7,7.26,7,6.42,8,7.91
5,5.68,5,4.74,5,5.73,8,6.89
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->

* * *

<section class="references">

## References

-   Anscombe, Francis J. 1973. "Graphs in Statistical Analysis." _The American Statistician_ 27 (1). \[American Statistical Association, Taylor & Francis, Ltd.]: 17–21. <http://www.jstor.org/stable/2682899>.

</section>

<!-- /.references -->

<!-- <license> -->

## License

The data files (databases) are licensed under an [Open Data Commons Public Domain Dedication & License 1.0][pddl-1.0] and their contents are licensed under [Creative Commons Zero v1.0 Universal][cc0]. The software is licensed under [Apache License, Version 2.0][apache-license].

<!-- </license> -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

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

## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-anscombes-quartet.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-anscombes-quartet

[test-image]: https://github.com/stdlib-js/datasets-anscombes-quartet/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-anscombes-quartet/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-anscombes-quartet?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-anscombes-quartet.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-anscombes-quartet/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/deno
[umd-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/umd
[esm-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/esm
[branches-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/blob/main/branches.md

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[csv]: https://tools.ietf.org/html/rfc4180

[anscombes-quartet]: https://en.wikipedia.org/wiki/Anscombe%27s_quartet

[francis-anscombe]: https://en.wikipedia.org/wiki/Francis_Anscombe

</section>

<!-- /.links -->
