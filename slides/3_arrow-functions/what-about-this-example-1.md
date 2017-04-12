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

note:
* The `this` in `mySecondFunction` is not bound to anything and defaults to `Window`
