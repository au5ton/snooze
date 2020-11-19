# snooze

![Node.js Package](https://github.com/au5ton/snooze/workflows/Node.js%20Package/badge.svg) [![npm (scoped)](https://img.shields.io/npm/v/@au5ton/snooze)](https://www.npmjs.com/@au5ton/snooze) ![npm type definitions](https://img.shields.io/npm/types/@au5ton/snooze)

snippet to mimick time.sleep() with promises

```js
const snooze = (ms) => new Promise(resolve => setTimeout(resolve, ms));
```