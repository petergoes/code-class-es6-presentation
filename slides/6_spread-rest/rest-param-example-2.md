##  Rest param example 2

```js
function average(...grades) {
    const total = grades.reduce((sum, x) => sum + x, 0);
    return total / grades.length;
}

console.log( average(1,2,3,4,5) ); // 3
console.log( average(1,2,3,4) );   // 2.5
console.log( average(3,4,5) );     // 4
```
