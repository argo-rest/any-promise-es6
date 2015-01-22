# AnyPromise adapter for ES6

[AnyPromise](https://github.com/argo-rest/any-promise) adapter for
ES6.

It is a somewhat tautological implementation that just exposes ES6
Promises as-is.

## Usage

This adapter is implemented as an ES6 module which can be installed
with [jspm](https://jspm.io) and loaded via
[SystemJS](https://github.com/systemjs/systemjs) as follows:

``` javascript
import {Promise} from 'any-promise-es6';

function answer() {
    return Promise.resolve(42);
}
```
