# snooze

snippet to mimick time.sleep() with promises

```js
const snooze = (ms) => new Promise(resolve => setTimeout(resolve, ms));
```