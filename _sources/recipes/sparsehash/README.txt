.. _`sparsehash`:

sparsehash
==========

An extremely memory-efficient hash_map implementation. 2 bits/entry overhead! The SparseHash library contains several hash-map implementations, including implementations that optimize for space or speed.  These hashtable implementations are similar in API to SGI's hash_map class and the tr1 unordered_map class, but with different performance characteristics. It's easy to replace hash_map or unordered_map by sparse_hash_map or dense_hash_map in C++ code.  They also contain code to serialize and unserialize from disk.

======== ===========
Home     https://github.com/sparsehash/sparsehash
Versions 2.0.3, 2.0.2
License  
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sparsehash/2.0.3
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install sparsehash

and update with::

   conda update sparsehash


