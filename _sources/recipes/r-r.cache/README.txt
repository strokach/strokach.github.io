.. _`r-r.cache`:

r-r.cache
=========

Memoization can be used to speed up repetitive and computational expensive function calls.  The first time a function that implements memoization is called the results are stored in a cache memory.  The next time the function is called with the same set of parameters, the results are momentarily retrieved from the cache avoiding repeating the calculations.  With this package, any R object can be cached in a key-value storage where the key can be an arbitrary set of R objects.  The cache memory is persistent (on the file system).

======== ===========
Home     https://github.com/HenrikBengtsson/R.cache
Versions 0.12.0
License  LGPL (>= 2.1)
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-r.cache
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-r.cache

and update with::

   conda update r-r.cache


