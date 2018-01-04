# kribo-gutil

This is a small gulp util app 


## Usage

```javascript
var gutil = require('kribo-gutil');

gutil.log('stuff happened', 'Really it did', gutil.colors.magenta('123'));

```

### log(msg...)

Logs stuff. Already prefixed with [gulp] and all that. If you pass in multiple arguments it will join them by a space.

The default gulp coloring using gutil.colors.<color>:
```
values (files, module names, etc.) = cyan
numbers (times, counts, etc) = magenta
```

### colors

Is an instance of [chalk](https://github.com/sindresorhus/chalk).