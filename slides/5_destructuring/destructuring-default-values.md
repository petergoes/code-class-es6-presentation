### Destructuring default values

```js
const pos = { x: 100, y: 200 };
const { x = 10, y = 10, w = 50, h = 50 } = pos;

console.log(x); // 100
console.log(y); // 200
console.log(w); // 50
console.log(h); // 50
```
