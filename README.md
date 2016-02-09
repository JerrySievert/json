# JSON Formatter

## Usage

```
$ npm install json-nice
```

```js
var format = require('json-nice');

console.log(format(obj));
```

### Options

Rendering can be customized by adding options:

```js
var options = {
  indent: '\t' // indent using tab
};

format(obj, options);
```
