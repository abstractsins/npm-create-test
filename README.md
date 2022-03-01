@abstractsins/npm-create-test

![npm (scoped)](https://img.shields.io/npm/v/@abstractsins/test?style=for-the-badge)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@abstractsins/test)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/abstractsins/npm-create-test?style=for-the-badge)
(https://github.com/abstractsins/npm-create-test)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```