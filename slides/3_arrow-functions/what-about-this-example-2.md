```js
const obj = {
    myFunction() {

        const mySecondFunction = () => console.log(this);

        console.log(this);  // Object {}
        mySecondFunction(); // Object {}
    }
};
obj.myFunction();
```

note:
* With an arrow function, the scope of `this` is inherit from the parent
