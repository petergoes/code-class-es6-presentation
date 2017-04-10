### Syntax

```js
// es5
var returnTen = function () { return 10; }
var doubleMe = function(x) { return x * 2; }
var doubleUs = function(x, y) { return (x * 2) + (y * 2); }
var logAndReturn = function(x) {
    console.log(x);
    return x;
}
```

```js
//es6
const returnTen = () => 10;
const doubleMe = x => x * 2;
const doubleUs = (x, y) => (x * 2) + (y * 2);
const logAndReturn = x => {
    console.log(x);
    return x;
}
```
