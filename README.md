Quiver check
============

Argument, state and other invariant checks for your programs.

[![Build Status](https://travis-ci.org/QuiverDart/quiver_check.svg?branch=master)](https://travis-ci.org/QuiverDart/quiver_check)
[![Coverage Status](https://img.shields.io/coveralls/QuiverDart/quiver_check.svg)](https://coveralls.io/r/QuiverDart/quiver_check)

[API Docs](http://www.dartdocs.org/documentation/quiver_check/latest) are available.

## quiver.check

`checkArgument` throws `ArgumentError` if the specified argument check expression
is false.

`checkListIndex` throws `RangeError` if the specified index is out of bounds.

`checkNotNull` throws `ArgumentError` if the specified argument is null.

`checkState` throws `StateError` if the specified state check expression is
false.
