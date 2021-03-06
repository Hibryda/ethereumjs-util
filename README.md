# SYNOPSIS
[![NPM Package](https://img.shields.io/npm/v/ethereumjs-util.svg?style=flat-square)](https://www.npmjs.org/package/ethereumjs-util)
[![Build Status](https://img.shields.io/travis/ethereumjs/ethereumjs-util.svg?branch=master&style=flat-square)](https://travis-ci.org/ethereumjs/ethereumjs-util)
[![Coverage Status](https://img.shields.io/coveralls/ethereumjs/ethereumjs-util.svg?style=flat-square)](https://coveralls.io/r/ethereumjs/ethereumjs-util)
[![Gitter](https://img.shields.io/gitter/room/ethereum/ethereumjs-lib.svg?style=flat-square)](https://gitter.im/ethereum/ethereumjs-lib) or #ethereumjs on freenode

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)



A collection of utility functions for ethereum. It can be used in node.js or can be in the browser with browserify.
*This version is forked and adjusted to work in NW.js. Keccakjs fails to detect browser environment, thus keccakjs dependency was replaced by keccakjs-browseronly one. Also, for convenience rather than out of real need secp is forcefully set to use js fallback.*
_Remember, it's just workaround. Do not use this in production._

# API
[./docs/](./docs/index.md)

# LICENSE
MPL-2.0
