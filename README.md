Gavin's Grunt Setup
===========

You only have to do these steps once:
* Install [NodeJS](http://nodejs.org/)
* Install [Grunt](http://gruntjs.com/getting-started) (`npm install -g grunt-cli`)


In your project:
```
$ wget https://raw.github.com/gavinblair/grunt-setup/master/setup.sh
$ ./setup.sh
(wait, answer the questions it asks)
$ grunt
```

This will start a watcher for `.js` files in the `js` directory. Every time you save a `js` file, it will be linted with [JSHint](http://www.jshint.com/), minified and all of your [QUnit](http://qunitjs.com/) tests will run.

Put all tests in `js/test/tests.js`.

Enjoy!

[gav](http://gavinblair.github.com)
