*This repository is a mirror of the [component](http://component.io) module [yuehu/valid-email](http://github.com/yuehu/valid-email). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yuehu-valid-email`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# valid-email

Valid an Email Address.

[![Build Status](https://travis-ci.org/yuehu/valid-email.png?branch=master)](https://travis-ci.org/yuehu/valid-email)

## Installation

Install with [component(1)](http://component.io):

    $ component install yuehu/valid-email

## API

The validation is async.

```js
var valid = require('valid-email');
valid(email, function(res) {
    // res.valid ?
    // res.hint
});
```

### .MAILGUN_KEY

Reset `valid.MAILGUN_KEY` to `null` to disable mailgun email address validation.

```js
valid.MAILGUN_KEY = null;
```

## License

MIT
