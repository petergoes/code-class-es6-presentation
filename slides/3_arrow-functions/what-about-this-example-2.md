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
