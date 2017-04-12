### Destructuring from a function

```js
function getStudent() {
    return {
        id: 1,
        firstName: 'Peter',
        lastName: 'Goes',
        grade: 7.0
    };
}

const { id, grade } = getStudent();

console.log(id);    // 1
console.log(grade); // 7.0
```
