##  Computed property es5

```js
const key = 'diff';
const value = -256;

const obj = {};

obj[key] = value;
obj[`${key}Abs`] = Math.abs(value);

console.log(obj); // { "diff": -256, "diffAbs": 256 }
```

note:
* You need to define the object before you can add computed properties
