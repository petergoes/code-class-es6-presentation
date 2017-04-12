### Normal function vs arrow function

```js
const arr = [1, 2, 3];

const newArr = arr.map(function(number) {
    return number * 2;
});

console.log(newArr); // [2, 4, 6];
```

```js
const arr = [1, 2, 3];

const newArr = arr.map(number => number * 2);

console.log(newArr); // [2, 4, 6];
```
