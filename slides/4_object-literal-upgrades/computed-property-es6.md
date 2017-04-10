##  Computed property es6

```js
const key = 'diff';
const value = -256;

const obj = {
   [key]: value,
   [`${key}Abs`]: Math.abs(value)
};

console.log(obj); // { "diff": -256, "diffAbs": 256 }
```
