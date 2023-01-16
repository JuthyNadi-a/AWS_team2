# null_or_empty

[![CI/CD](https://github.com/JuthyNadi-a/AWS_team2/actions/workflows/main.yml/badge.svg)](https://github.com/JuthyNadi-a/AWS_team2/actions/workflows/main.yml)

A Node.js package that checks, if a given string is null or empty.



## Usage

First, install the package using npm:

    npm install /null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
