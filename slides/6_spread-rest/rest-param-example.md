## Rest example 1

```js
const student = ['Peter', 1, 7.5, 6, 8.5];

const [name, id, ...grades] = student;

console.log(name);   // "Peter"
console.log(id);     // 1
console.log(grades); // [7.5, 6, 8.5]
```

note:
1. create a `const` with the name `name` and assign the first item of `student`
2. create a `const` with the name `id` and assign the second item of `student`
3. create a `const` (array) with the name `grades` and assign the all other items from `student`
