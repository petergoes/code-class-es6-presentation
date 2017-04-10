##  Don't use arrow functions

```js
const obj = {
  foo: function() { console.log(this); } // { "foo": ... }
}

const obj2 = {
  foo() { console.log(this); }           // { "foo": ... }
}

const obj3 = {
  foo: () => { console.log(this); }      // undefined
}
```
