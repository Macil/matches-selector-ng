# matches-selector-ng

[![Circle CI](https://circleci.com/gh/AgentME/matches-selector-ng.svg?style=shield)](https://circleci.com/gh/AgentME/matches-selector-ng)
[![npm version](https://badge.fury.io/js/matches-selector-ng.svg)](https://badge.fury.io/js/matches-selector-ng)

Check if an element matches a given selector. Uses the native
[`matches` method](https://developer.mozilla.org/en-US/docs/Web/API/Element/matches)
if present. For use with a commonjs bundler such as browserify.

## Installation

    $ yarn add matches-selector-ng

## Example

```js
var matches = require('matches-selector-ng');
matches(el, 'ul li a');
// => true or false
```

## Types

[Flow](https://flowtype.org/) type declarations for this module are included!
If you are using Flow, they won't require any configuration to use.
