# PEP ideas

In this page I plan to list all PEP ideas that I encountered while developing [various python libraries](https://github.com/smarie/ALL_OF_THE_ABOVE#python). Each idea is then detailed in the [issues page](https://github.com/smarie/python-pep-ideas/issues) for discussion.

## from [`getversion`](https://smarie.github.io/python-getversion/)

 * [an api to get the version of anything reliably](https://github.com/smarie/python-pep-ideas/issues)

## from [`makefun`](https://smarie.github.io/python-makefun)

 * [a better functools (more signature-preserving, and with more features such as edition)](https://github.com/smarie/python-pep-ideas/issues/2)

## from [`decopatch`](https://smarie.github.io/python-decopatch)

 * [a way to know if a frame is a decorator call](https://github.com/smarie/python-pep-ideas/issues/3)
 
 * More generally, a better way to handle decorators in the python language could be good (see [this discussion](https://smarie.github.io/python-decopatch/pep_proposal/))

## from [`mini-lambda`](https://smarie.github.io/python-mini-lambda)

 * [more user-friendly lambda functions](https://github.com/smarie/python-pep-ideas/issues/4)

### from [`pyfields`](https://smarie.github.io/python-pyfields/)

 * [ability to override `__slots__` descriptors](https://github.com/smarie/python-pep-ideas/issues/5)

 * [set-only descriptors (fast-get descriptors)](https://github.com/smarie/python-pep-ideas/issues/6)
 
 * [possible bug with `super()` in combination with descriptor](https://github.com/smarie/python-pep-ideas/issues/7)

## from  [`fprules`](https://smarie.github.io/python-fprules) 

 * Support `make`-like file pattern rules easily, to be used for example in build tools such as `doit`. This package is a demo of the concept, but it could be directly integrated to the `glob` package ? Or at least I would appreciate feedback :)
 