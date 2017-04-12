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

note:
* Do not use arrow functions in property shorthands, it will mess with the `this`
