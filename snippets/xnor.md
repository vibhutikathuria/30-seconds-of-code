---
title: xor
tags: math,logic,beginner
---

Checks if both of the arguments is `false` or `true`.

- Use the logical or (`||`), and (`&&`) and not (`!`) operators on the two given values to create the logical xnor.

```js
const xnor = (a, b) => (!( a && b ) || ( a && b ));
```

```js
xor(true, true); //true 
xor(true, false); // false
xor(false, true); // false
xor(false, false); // true