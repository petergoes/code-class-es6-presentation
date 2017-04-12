### Renaming values

```js
const rect = { x: 100, y: 200, w: 30, h: 40 };

const { w: width, h: height } = rect;

console.log(width);  // 30
console.log(height); // 40

```

note:
1. Is `w` in `rect` object? Yes, make a new `const` with name `width` and use `w` value from `rect` object
2. Is `h` in `rect` object? Yes, make a new `const` with name `height` and use `h` value from `rect` object
