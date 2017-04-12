### Spread into array

```js
const name = 'Peter';
const id = 1;
const grades = [7.5, 6, 8.5];

const student = [name, id, ...grades];

console.log(student); // ["Peter", 1, 7.5, 6, 8.5]
```

note:
* create a flat array with the first item `name`, the second item `id` and then all items from `grades`
