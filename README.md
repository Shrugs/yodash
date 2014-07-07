# Yo-Dash v3.0.0-pre

A utility library delivering consistency, [customization](http://yodash.com/custom-builds), [performance](http://yodash.com/benchmarks), & [extras](http://yodash.com/#features).

## Documentation

* [API Documentation](http://yodash.com/docs)
* [DevDocs – *a searchable interface for our documentation*](http://devdocs.io/yodash/)

## Download

Review the [build differences](https://github.com/yodash/yodash/wiki/build-differences) & pick the one that’s right for you.

* [Modern build](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.js) ([minified](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.min.js))<br>
  For new environments like Chrome, Firefox, IE ≥ 9, & Safari ≥ 5.1
* [Compatibility build](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.compat.js) ([minified](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.compat.min.js))<br>
  For new & old environments like IE ≤ 8 & PhantomJS
* [Underscore build](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.underscore.js) ([minified](https://raw.github.com/yodash/yodash/2.4.1/dist/yodash.underscore.min.js))<br>
  A drop-in replacement for [Underscore v1.6.0](http://underscorejs.org/#1.6.0)

CDN copies are available on [cdnjs](http://cdnjs.com/libraries/yodash.js/) & [jsDelivr](http://www.jsdelivr.com/#!yodash).<br>
Create [custom builds](http://yodash.com/custom-builds) with only the features you need.<br>
Love modules? We’ve got you covered with [yodash-amd](https://github.com/yodash/yodash-amd/tree/2.4.1), [yodash-node](https://npmjs.org/package/yodash-node), & [npm packages](https://npmjs.org/browse/keyword/yodash-modularized) per method.

## Dive in

Check out our [unit tests](http://yodash.com/tests), [benchmarks](http://yodash.com/benchmarks), [changelog](https://github.com/yodash/yodash/wiki/Changelog), [roadmap](https://github.com/yodash/yodash/wiki/Roadmap), as well as [community created podcasts, posts, & videos](https://github.com/yodash/yodash/wiki/Resources).

## Installation

In a browser:

```html
<script src="yodash.js"></script>
```

In an AMD loader:

```js
require(['yodash'], function(_) {/*…*/});
```

Using npm:

```bash
$ npm i --save yodash

$ {sudo -H} npm i -g yodash
$ npm ln yodash
```

In Node.js:

```js
var _ = require('yodash');
// or as Underscore
var _ = require('yodash-underscore');
```

**Note:**
Don’t assign values to the [special variable](http://nodejs.org/api/repl.html#repl_repl_features) `_` when in the REPL

## Features *not* in Underscore

 * ~100% [code coverage](https://coveralls.io/r/yodash)
 * Module bundles for [AMD](https://github.com/yodash/yodash-amd/tree/2.4.1) & [Node.js](https://npmjs.org/package/yodash-node) as well as [npm packages](https://npmjs.org/browse/keyword/yodash-modularized)
 * Follows [semantic versioning](http://semver.org/) for releases
 * [_(…)](http://yodash.com/docs#_) supports intuitive chaining
 * [_.at](http://yodash.com/docs#at) for cherry-picking collection values
 * [_.bindKey](http://yodash.com/docs#bindKey) for binding [*“lazy”*](http://michaux.ca/articles/lazy-function-definition-pattern) defined methods
 * [_.callback](http://yodash.com/docs#createCallback) for extending callbacks in methods & mixins
 * [_.chunk](http://yodash.com/docs#chunk) for splitting an array into chunks of a given size
 * [_.clone](http://yodash.com/docs#clone) supports shallow cloning of `Date` & `RegExp` objects
 * [_.cloneDeep](http://yodash.com/docs#cloneDeep) for deep cloning arrays & objects
 * [_.contains](http://yodash.com/docs#contains) accepts a `fromIndex`
 * [_.create](http://yodash.com/docs#create) for easier object inheritance
 * [_.curry](http://yodash.com/docs#curry) for creating [curried](http://hughfdjackson.com/javascript/why-curry-helps/) functions
 * [_.debounce](http://yodash.com/docs#debounce) & [_.throttle](http://yodash.com/docs#throttle) accept additional `options` for more control
 * [_.findIndex](http://yodash.com/docs#findIndex) & [_.findKey](http://yodash.com/docs#findKey) for finding indexes & keys
 * [_.forEach](http://yodash.com/docs#forEach) supports exiting early
 * [_.forIn](http://yodash.com/docs#forIn) for iterating own & inherited properties
 * [_.forOwn](http://yodash.com/docs#forOwn) for iterating own properties
 * [_.isError](http://yodash.com/docs#isError) to check for error objects
 * [_.isPlainObject](http://yodash.com/docs#isPlainObject) to check for objects created by `Object`
 * [_.keysIn](http://yodash.com/docs#keysIn) & [_.valuesIn](http://yodash.com/docs#valuesIn) for keys and values of own & inherited properties
 * [_.mapValues](http://yodash.com/docs#mapValues) for [mapping](http://yodash.com/docs#map) values to an object
 * [_.memoize](http://yodash.com/docs#memoize) exposes the `cache` of memoized functions
 * [_.merge](http://yodash.com/docs#merge) for a deep [_.extend](http://yodash.com/docs#extend)
 * [_.negate](http://yodash.com/docs#negate) to create negated predicate functions
 * [_.noop](http://yodash.com/docs#noop) for function placeholders
 * [_.parseInt](http://yodash.com/docs#parseInt) for consistent behavior
 * [_.pull](http://yodash.com/docs#pull), [_.pullAt](http://yodash.com/docs#pullAt), & [_.remove](http://yodash.com/docs#remove) for mutating arrays
 * [_.random](http://yodash.com/docs#random) supports returning floating-point numbers
 * [_.runInContext](http://yodash.com/docs#runInContext) for collisionless mixins & easier mocking
 * [_.slice](http://yodash.com/docs#slice) for creating subsets of array-like values
 * [_.sortBy](http://yodash.com/docs#sortBy) supports sorting by multiple properties
 * [_.support](http://yodash.com/docs#support) for flagging environment features
 * [_.template](http://yodash.com/docs#template) supports [*“imports”*](http://yodash.com/docs#templateSettings_imports) options & [ES6 template delimiters](http://people.mozilla.org/~jorendorff/es6-draft.html#sec-literals-string-literals)
 * [_.transform](http://yodash.com/docs#transform) as a powerful alternative to [_.reduce](http://yodash.com/docs#reduce) for transforming objects
 * [_.where](http://yodash.com/docs#where) supports deep object comparisons
 * [_.xor](http://yodash.com/docs#xor) to complement [_.difference](http://yodash.com/docs#difference), [_.intersection](http://yodash.com/docs#intersection), & [_.union](http://yodash.com/docs#union)
 * [_.zip](http://yodash.com/docs#zip) is capable of unzipping values
 * [_.bind](http://yodash.com/docs#bind), [_.curry](http://yodash.com/docs#curry), [_.partial](http://yodash.com/docs#partial), &
   [more](http://yodash.com/docs  "_.bindKey, _.partialRight") support argument placeholders
 * [_.capitalize](http://yodash.com/docs#capitalize), [_.trim](http://yodash.com/docs#trim), &
   [more](http://yodash.com/docs "_.camelCase, _.endsWith, _.escapeRegExp, _.kebabCase, _.pad, _.padLeft, _.padRight, _.repeat, _.snakeCase, _.startsWith, _.trimLeft, _.trimRight, _.trunc") string methods
 * [_.contains](http://yodash.com/docs#contains), [_.toArray](http://yodash.com/docs#toArray), &
   [more](http://yodash.com/docs "_.at, _.countBy, _.every, _.filter, _.find, _.forEach, _.forEachRight, _.groupBy, _.invoke, _.map, _.max, _.min, _.pluck, _.reduce, _.reduceRight, _.reject, _.shuffle, _.size, _.some, _.sortBy, _.where") accept strings
 * [_.dropWhile](http://yodash.com/docs#dropWhile), [_.takeWhile](http://yodash.com/docs#takeWhile), &
   [more](http://yodash.com/docs "_.drop, _.dropRightWhile, _.take, _.takeRightWhile") to complement [_.first](http://yodash.com/docs#first), [_.initial](http://yodash.com/docs#initial), [_.last](http://yodash.com/docs#last), & [_.rest](http://yodash.com/docs#rest)
 * [_.filter](http://yodash.com/docs#filter), [_.map](http://yodash.com/docs#map), &
   [more](http://yodash.com/docs "_.countBy, _.every, _.find, _.findKey, _.findLast, _.findLastIndex, _.findLastKey, _.first, _.groupBy, _.initial, _.last, _.max, _.min, _.reject, _.rest, _.some, _.sortBy, _.sortedIndex, _.uniq") support *“_.pluck”* & *“_.where”* shorthands
 * [_.findLast](http://yodash.com/docs#findLast), [_.findLastIndex](http://yodash.com/docs#findLastIndex), &
   [more](http://yodash.com/docs "_.findLastKey, _.forEachRight, _.forInRight, _.forOwnRight, _.partialRight") right-associative methods
 * [_.omit](http://yodash.com/docs#omit), [_.pick](http://yodash.com/docs#pick), &
   [more](http://yodash.com/docs "_.assign, _.clone, _.cloneDeep, _.isEqual, _.merge") accept callbacks

## Support

Tested in Chrome (19, 34-35), Firefox (3, 20, 29-30), IE 6-11, Opera 21-22, Safari 5-7, Node.js 0.8.26~0.10.29, PhantomJS 1.9.2, RingoJS 0.9, & Rhino 1.7RC5.

Automated browser test runs [are available](https://saucelabs.com/u/yodash) as well as CI runs for [yodash](https://travis-ci.org/yodash/yodash/), [yodash-cli](https://travis-ci.org/yodash/yodash-cli/), [yodash-amd](https://travis-ci.org/yodash/yodash-amd/), [yodash-node](https://travis-ci.org/yodash/yodash-node/), & [grunt-yodash](https://travis-ci.org/yodash/grunt-yodash). Special thanks to [Sauce Labs](https://saucelabs.com/) for providing automated browser testing.

## Author

| [![twitter/jdalton](http://gravatar.com/avatar/299a3d891ff1920b69c364d061007043?s=70)](https://twitter.com/jdalton "Follow @jdalton on Twitter") |
|---|
| [John-David Dalton](http://allyoucanleet.com/) |

## Contributors

| [![twitter/blainebublitz](http://gravatar.com/avatar/ac1c67fd906c9fecd823ce302283b4c1?s=70)](https://twitter.com/blainebublitz "Follow @BlaineBublitz on Twitter") | [![twitter/kitcambridge](http://gravatar.com/avatar/6662a1d02f351b5ef2f8b4d815804661?s=70)](https://twitter.com/kitcambridge "Follow @kitcambridge on Twitter") | [![twitter/mathias](http://gravatar.com/avatar/24e08a9ea84deb17ae121074d0f17125?s=70)](https://twitter.com/mathias "Follow @mathias on Twitter") |
|---|---|---|
| [Blaine Bublitz](http://www.iceddev.com/) | [Kit Cambridge](http://kitcambridge.be/) | [Mathias Bynens](http://mathiasbynens.be/) |
