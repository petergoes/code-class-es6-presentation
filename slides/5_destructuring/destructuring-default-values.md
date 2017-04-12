### Destructuring default values

```js
const pos = { x: 100, y: 200 };
const { x = 10, y = 10, w = 50, h = 50 } = pos;

console.log(x); // 100
console.log(y); // 200
console.log(w); // 50
console.log(h); // 50
```

note:
1. is `x` in the `pos` object? Yes, make new `const` with name `x` and assign `pos` object value
2. is `y` in the `pos` object? Yes, make new `const` with name `y` and assign `pos` object value
3. is `w` in the `pos` object? No, make new `const` with name `w` and assign default value `50`
4. is `h` in the `pos` object? No, make new `const` with name `h` and assign default value `50`
