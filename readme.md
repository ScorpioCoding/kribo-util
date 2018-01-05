# kribo-util

Utility functions for gulp plugins

[![MIT license][MIT-image]][MIT-url] [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependencies][dep-image]][dep-url] [![devDependencies][devdep-image]][devdep-url]

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

### date

Is an instance of [dateformat](https://github.com/felixge/node-dateformat).



[npm-url]: https://www.npmjs.com/package/kribo-util
[npm-image]: https://img.shields.io/npm/v/kribo-util.svg?style=flat

[travis-url]: https://travis-ci.org/ScorpioCoding/kribo-util
[travis-image]: https://travis-ci.org/ScorpioCoding/kribo-util.svg?branch=master

[dep-url]: https://david-dm.org/ScorpioCoding/kribo-util
[dep-image]: http://img.shields.io/david/ScorpioCoding/kribo-util.svg?style=flat
[devdep-url]: https://david-dm.org/ScorpioCoding/kribo-util?type=dev
[devdep-image]: https://david-dm.org/ScorpioCoding/kribo-util/dev-status.svg?style=flat

[MIT-url]: http://opensource.org/licenses/MIT
[MIT-image]: http://img.shields.io/badge/license-MIT-brightgreen.svg








