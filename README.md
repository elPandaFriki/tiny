# @davidperera/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@davidperera/tiny.svg)](https://www.npmjs.com/package/@davidperera/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@davidperera/tiny.svg)](https://www.npmjs.com/package/@davidperera/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @davidperera/tiny
```

## Usage

```js
const tiny = require("@davidperera/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
