### Object destructuring

```js
const student = {
    id: 1,
    firstName: 'Peter',
    lastName: 'Goes',
    grade: 7.0
};

const { id, grade } = student;

console.log(id);    // 1
console.log(grade); // 7.0
```
