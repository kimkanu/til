---
title: Checking if a string starts with a specific substring in JavaScript
tags:
    - javascript
date: 2023-07-04T12:59:24.428Z
icon: javascript
---

```js
// Javascript code example

const string = 'hello world';

const toCheckString = 'he';

let result = string.lastIndexOf(toCheckString, 0) === 0;
if(result) {
    console.warn('The string starts with "he".');
}
else {
    console.warn(`The string does not starts with "he".`);
}
```

