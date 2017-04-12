```js
for (let i = 0; i < 10; i++) {
    setTimeout(function() {
        console.log('The number is:', i);
    }, 1000);
}
console.log(i); // error
```

note:
* The number is: n
* log statement throws error, i in block scope
