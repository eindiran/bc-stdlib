# bc-stdlib
A small standard library for `GNU bc`. This library is in very large part inspired by a list of functions provided by [phodd.net](http://phodd.net/gnu-bc/code/funcs.bc) and the [phodd.net GNU bc FAQ](http://phodd.net/gnu-bc/bcfaq.html). Some of the trigonometric are modified versions of functions found in the `extensions.bc` component of `x-bc`, found [here](http://x-bc.sourceforge.net/extensions_bc.html).

These are just a number of functions that I find convenient to always have available (without manually redefining them) when I'm using `bc`. Many of these functions can be used with other flavors of `bc`, but may require (significant) reworking. They should not be expected to work out of the box with a `bc` other than `GNU bc`.
