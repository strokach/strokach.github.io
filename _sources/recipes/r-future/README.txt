.. _`r-future`:

r-future
========

A Future API for R is provided. In programming, a future is an abstraction for a value that may be available at some point in the future. The state of a future can either be unresolved or resolved. As soon as it is resolved, the value is available. Futures are useful constructs in for instance concurrent evaluation, e.g. multicore parallel processing and distributed processing on compute clusters. The purpose of this package is to provide a lightweight interface for using futures in R. Functions 'future()' and 'value()' exist for creating futures and requesting their values. An infix assignment operator '%<=%' exists for creating futures whose values are accessible by the assigned variables (as promises). This package implements the synchronous "lazy" and "eager" futures, and the asynchronous "multicore" future (not on Windows). Additional types of futures are provided by other packages enhancing this package.

======== ===========
Home     https://github.com/HenrikBengtsson/future
Versions 0.9.0
License  LGPL (>= 2.1)
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-future
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-future

and update with::

   conda update r-future


