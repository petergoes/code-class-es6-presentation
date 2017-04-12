```js
const width = 200;
if (true === true) {
    const height = 300;
}

function myFunction() {
    const x = 100;
    console.log(width); // 200
}
myFunction();

console.log(width);  // 200
console.log(height); // error <-- this throws an error
console.log(x);      // error
```

note:
* x is only available in myFunction
* height is only available in if block!
