# @arisa_dev/tiny

[![GitHub issues](https://img.shields.io/badge/npm-1.0.0-blue)](https://github.com/schabibi1/tiny)

## INstall

```
$ npm install @arisa_dev/tiny
```

## Usage

```javascript
const tiny = require("@arisa_dev/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```