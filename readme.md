Crash.js
---
for when `process.exit()` just isn't enough.

example use:
JS:
```javascript
const crash = require('crash');
if (user.hasWorkingWindowsComputer) {
    crash();
}
```

if you have a problem, email iwontlookatthis@hecancanyou.xyz