```js
var width = 200;
if (true === true) {
    var height = 300;
}

function myFunction() {
    var x = 100;
    console.log(width); // 200
}
myFunction();

console.log(width);  // 200
console.log(height); // 300
console.log(x);      // error
```

note:
* x is only available in myFunction
* height is global scoped (not in function scope)
