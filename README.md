# my-map-function

this is my npm function practice.

## How to use

### Install

```
npm i my-map-function
```

### Usage

```js
const myMap = require("yi-en/my-map-function");
const array = [1, 2, 3, 4];
const callbackFn = (element, index) => elenment * 2;
const res = myMap(callbackFn)(array);

console.log(res);
```
