# sc-gutil



ScorpioCoding Gulp Utility functions for gulp plugins

[![sc up/down][sc-image]][sc-url] [![Greenkeeper badge][greenkeeper-image]][greenkeeper-url] [![MIT license][MIT-image]][MIT-url] [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependencies][dep-image]][dep-url] [![devDependencies][devdep-image]][devdep-url]

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



[npm-url]: https://www.npmjs.com/package/sc-gutil
[npm-image]: https://img.shields.io/npm/v/sc-gutil.svg?style=flat

[travis-url]: https://travis-ci.org/ScorpioCoding/sc-gutil
[travis-image]: https://travis-ci.org/ScorpioCoding/sc-gutil.svg?branch=master

[dep-url]: https://david-dm.org/ScorpioCoding/sc-gutil
[dep-image]: http://img.shields.io/david/ScorpioCoding/sc-gutil.svg?style=flat
[devdep-url]: https://david-dm.org/ScorpioCoding/sc-gutil?type=dev
[devdep-image]: https://david-dm.org/ScorpioCoding/sc-gutil/dev-status.svg?style=flat

[MIT-url]: http://opensource.org/licenses/MIT
[MIT-image]: http://img.shields.io/badge/license-MIT-brightgreen.svg

[greenkeeper-url]: https://greenkeeper.io/
[greenkeeper-image]: https://badges.greenkeeper.io/ScorpioCoding/sc-gutil.svg

[sc-url]: https://scorpiocoding.net
[sc-image]: https://img.shields.io/website-up-down-green-red/http/shields.io.svg?label=scorpiocoding.net







