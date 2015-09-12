# Demo: imports are views

In ES6 modules, imports are read-only views on exports. The code in this repository demonstrates that fact.

Description of the directories:

* `es6`: ES6 code that demonstrates that imports are views on exports.
* `es6_for_babel`: A version of `es/` that can be transpiled by Babel.
* `commonjs_transpiled`: The output produced by Babel when it transpiles `es6_for_babel/`.
* `commonjs`: A hand-written CommonJS version of `es6/`.
