```js
const obj = {};

obj.myFunction = function () {

    const mySecondFunction = function () {
        console.log(this);
    }

    console.log(this);           // Object {}
    mySecondFunction();          // Window
    mySecondFunction.call(this); // Object {}
}

obj.myFunction();
```
