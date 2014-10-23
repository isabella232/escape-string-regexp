# escape-string-regexp [![Build Status](https://travis-ci.org/sindresorhus/escape-string-regexp.svg?branch=master)](https://travis-ci.org/sindresorhus/escape-string-regexp)

> Escape RegExp special characters


## Install

```sh
$ npm install --save escape-string-regexp
```


## Usage

```js
var escapeStringRegexp = require('escape-string-regexp');

var escapedString = escapeStringRegexp('how much $ for a unicorn?');
//=> how much \$ for a unicorn\?

new RegExp(escapedString);
```

## Browser use

```html
   <script src="dist/escape_string_regexp.js"></script>
```

### Compile new version to the browser

```sh
npm install
npm run compile
```

## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
