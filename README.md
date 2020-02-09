[![npm (scoped)](https://img.shields.io/github/issues/shaminGit/tiny.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)
[![npm bundle size (minified)](https://img.shields.io/github/license/shaminGit/tiny.svg)](https://www.npmjs.com/package/@bamblehorse/tiny)

# @npmdevtools/tiny

It's Amazing !

## Install

```
$ npm install @npmdevtools/tiny
```

## Usage

```js
import tiny from "@npmdevtools/tiny"

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
