### Spread into function

```js
function add(a, b) {
    return a + b;
}

const numbers = [2, 3];

const value = add(...numbers);

console.log(value); // 5
```
