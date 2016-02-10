.. _`r-matrixstats`:

r-matrixstats
=============

High-performing functions operating on rows and columns of matrices, e.g. col / rowMedians(), col / rowRanks(), and col / rowSds().  Functions optimized per data type and for subsetted calculations such that both memory usage and processing time is minimized.  There are also optimized vector-based methods, e.g. binMeans(), madDiff() and weightedMedians().

======== ===========
Home     https://github.com/HenrikBengtsson/matrixStats
Versions 0.50.1
License  Artistic-2.0
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-matrixstats
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-matrixstats

and update with::

   conda update r-matrixstats


