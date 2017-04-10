### Watch out

```js
const arr = [1, 2, 4];
arr[2] = 3;
console.log(arr); // [1, 2, 3]

const obj = { foo: 'bar' };
obj.foo = 'hello world';
console.log(obj.foo); // hello world

arr = []; // error
obj = {}; // error
```

note:
* Properties or array values can be modified
