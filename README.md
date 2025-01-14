# null_or_empty

[![Node CI](https://github.com/SneRam-0105/CI-CD_Demo2/actions/workflows/whatever.yml/badge.svg)](https://github.com/SneRam-0105/CI-CD_Demo2/actions/workflows/whatever.yml)

A simple Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT

## Added new line in readme
