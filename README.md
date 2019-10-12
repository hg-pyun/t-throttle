# t-throttle

The tiny throttle function

## Installation

```shell script
$ npm install t-throttle --save
```

## How to use

```js
const throttle = require('t-throttle');
const thFunc = throttle(() => {
  console.log('exec');
}, 1000);

for (let i = 0; i < 100; i++) {
  thFunc();
}
```
