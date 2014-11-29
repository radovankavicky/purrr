# lowliner

This is a functional programming (FP) library in the style of [underscore.js](http://underscorejs.org), [low-dash](https://lodash.com) and [lazy.js](http://danieltao.com/lazy.js/).

## Functions

### Lists

* Apply a function to each element: `map()` returns transformed list, 
  `each()` returns original list, calling function for its side effects.

* `keep()` or `discard()` elements where predicate is true.

* `reduce()` and `reduce_right()` iteratively a list to a single value 
  by iteratively applying a binary function.
