Static Backbone app
===================

> based on "generator-webapp"

### setup
```
$ npm install
$ bower install //to install bower packages
$ grunt build //to get a ready to ship dist directory
$ heroku config:set BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-php //to fake a php app instead of a node.js app on heroku
```

### what's included:

- "requirejs": "~2.1.5"
- "requirejs-text": "~2.0.5"
- "backbone-amd": "~1.0.0"
- "underscore-amd": "~1.4.4"
- "jquery": "~1.9.1"
- "modernizr": "~2.6.2"
- "bootstrap": "~3.0.0"
- "font-awesome": "~3.2.1"
