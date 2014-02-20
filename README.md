*This repository is a mirror of the [component](http://component.io) module [lepture/sanitize](http://github.com/lepture/sanitize). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/lepture-sanitize`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# sanitize

sanitize html for safety.

[![Build Status](https://travis-ci.org/lepture/sanitize.png?branch=master)](https://travis-ci.org/lepture/sanitize)
[![Coverage Status](https://coveralls.io/repos/lepture/sanitize/badge.png)](https://coveralls.io/r/lepture/sanitize)


## Installation

Component install with:

    $ component install lepture/sanitize

SPM install with:

    $ spm install lepture/sanitize

## API

```
var sanitize = require('sanitize')
var html = sanitize('<script>alert('foo')</script><div>bar</div>')
```

## License

MIT
