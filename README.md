# PostCSS Critical Path [![Build Status][ci-img]][ci]

[PostCSS] plugin to separate critical path css.

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/tysonwolker/postcss-critical-path.svg
[ci]:      https://travis-ci.org/tysonwolker/postcss-critical-path

```css
.foo {
    /* Input example */
}
```

```css
.foo {
  /* Output example */
}
```

## Usage

```js
postcss([ require('postcss-critical-path') ])
```

See [PostCSS] docs for examples for your environment.
