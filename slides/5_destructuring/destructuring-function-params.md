### Destructuring function params

```js
const coordinates = { x: 100, y: 200 };

create(coordinates);

function create({x=10, y=10, w:width = 100, h:height = 100} = {}) {
    console.log(`x pos: ${x}`);       // x pos: 100
    console.log(`y pos: ${x}`);       // y pos: 200
    console.log(`width: ${width}`);   // width: 100
    console.log(`height: ${height}`); // height: 100
}
```

```
{x = 10, y = 10, w: width = 100, h: height = 100} = {}
```

note:
1. Is `w` in `coordinates`? No, create new `const` variable `width`, with a default value of `100`
2. Is `h` in `coordinates`? No, create new `const` variable `height`, with a default value of `100`
