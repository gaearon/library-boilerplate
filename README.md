library-boilerplate
=========================

An opinionated setup I plan to use for my libraries.

It has CommonJS and UMD builds via Babel and Webpack, ESLint, and Mocha.
It also has React-friendly examples folder with library code mapped to the sources.

If you use this, make sure to grep for “library-boilerplate” and replace every occurrence.
See `package.json` in the root and the example folder for the list of the available commands.

Note that this is an *opinionated* boilerplate. You might want to:

* Install `babel-preset-stage-2` instead of `babel-preset-stage-0` so you don’t depend on language features that might be gone tomorrow;
* Add `loose` mode in `.babelrc` by installing `babel-preset-es2015-loose`.

You have been warned.
