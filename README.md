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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Anscombe's Quartet

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Anscombe's quartet][anscombes-quartet].

<section class="intro">

[Anscombe's quartet][anscombes-quartet] is a set of `4` datasets which all have nearly identical simple statistical properties but vary considerably when graphed. [Anscombe][francis-anscombe] created the datasets to demonstrate why graphical data exploration should **precede** statistical data analysis and to show the effect of outliers on statistical properties.

</section>

<!-- /.intro -->









<section class="cli">



<section class="installation">

## Installation

To use as a general utility, install the CLI package globally

```bash
npm install -g @stdlib/datasets-anscombes-quartet-cli
```

</section>

<!-- CLI usage documentation. -->

<section class="usage">

## Usage

```text
Usage: anscombes-quartet [options]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->



<section class="examples">

## Examples

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

## See Also

-   <span class="package-name">[`@stdlib/datasets-anscombes-quartet`][@stdlib/datasets-anscombes-quartet]</span><span class="delimiter">: </span><span class="description">anscombe's quartet.</span>


</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

### Community

[![Chat][chat-image]][chat-url]

---

## Copyright

Copyright &copy; 2016-2026. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/datasets-anscombes-quartet-cli.svg
[npm-url]: https://npmjs.org/package/@stdlib/datasets-anscombes-quartet-cli

[test-image]: https://github.com/stdlib-js/datasets-anscombes-quartet/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/datasets-anscombes-quartet/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/datasets-anscombes-quartet?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/datasets-anscombes-quartet.svg
[dependencies-url]: https://david-dm.org/stdlib-js/datasets-anscombes-quartet/main

-->

[chat-image]: https://img.shields.io/badge/zulip-join_chat-brightgreen.svg
[chat-url]: https://stdlib.zulipchat.com

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/datasets-anscombes-quartet#cli
[cli-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/cli
[@stdlib/datasets-anscombes-quartet]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/deno
[deno-readme]: https://github.com/stdlib-js/datasets-anscombes-quartet/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/umd
[umd-readme]: https://github.com/stdlib-js/datasets-anscombes-quartet/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/tree/esm
[esm-readme]: https://github.com/stdlib-js/datasets-anscombes-quartet/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/datasets-anscombes-quartet/blob/main/branches.md

[pddl-1.0]: http://opendatacommons.org/licenses/pddl/1.0/

[cc0]: https://creativecommons.org/publicdomain/zero/1.0

[apache-license]: https://www.apache.org/licenses/LICENSE-2.0

[csv]: https://tools.ietf.org/html/rfc4180

[anscombes-quartet]: https://en.wikipedia.org/wiki/Anscombe%27s_quartet

[francis-anscombe]: https://en.wikipedia.org/wiki/Francis_Anscombe

</section>

<!-- /.links -->
