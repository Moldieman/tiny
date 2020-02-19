# @moldesurf/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@moldesurf/tiny.svg)](https://www.npmjs.com/package/@moldesurf/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@moldesurf/tiny.svg)](https://www.npmjs.com/package/@moldesurf/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @moldesurf/tiny
```

## Usage

```js
const tiny = require("@moldesurf/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
