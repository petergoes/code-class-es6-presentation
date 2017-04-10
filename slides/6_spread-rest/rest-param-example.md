## Rest example 1

```js
const student = ['Peter', 1, 7.5, 6, 8.5];

const [name, id, ...grades] = student;

console.log(name);   // "Peter"
console.log(id);     // 1
console.log(grades); // [7.5, 6, 8.5]
```
