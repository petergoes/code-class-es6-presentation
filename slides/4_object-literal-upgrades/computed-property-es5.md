##  Computed property es5

```js
const key = 'diff';
const value = -256;

const obj = {};

obj[key] = value;
obj[`${key}Abs`] = Math.abs(value);

console.log(obj); // { "diff": -256, "diffAbs": 256 }
```
