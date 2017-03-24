# Stardate Converter [![NPM version](https://img.shields.io/npm/v/stardate-converter.svg)](https://npmjs.com/package/stardate-converter) [![Build Status](https://travis-ci.org/zeroturnaround/stardate-converter.svg?branch=master)](https://travis-ci.org/zeroturnaround/stardate-converter)

**Stardate Converter** is a JavaScript library for converting common date to Star Trek stardate.

## Install

Get the latest version from NPM:

```
npm install stardate-converter --save
```

## Usage

```js
import stardateConverter from "stardate-converter";

console.log(stardateConverter.convert(new Date(2017, 9, 24)));
```

This will output:

```
-305249.32
```

## License

[MIT](https://github.com/zeroturnaround/stardate-converter/blob/master/LICENSE)
