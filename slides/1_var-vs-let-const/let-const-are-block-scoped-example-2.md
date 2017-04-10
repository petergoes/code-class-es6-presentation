```js
for (var i = 0; i < 10; i++) {
    setTimeout(function() {
        console.log('The number is:', i);
    }, 1000);
}
console.log(i); // 10
```

note:
* 10x The number is: 10
* log statement shows 10, i leaked in global scope
