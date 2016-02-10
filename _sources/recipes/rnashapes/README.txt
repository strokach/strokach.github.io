.. _`rnashapes`:

rnashapes
=========

RNAshape abstraction maps structures to a tree-like domain of shapes, retaining adjacency and nesting of structural features, but disregarding helix lengths. Shape abstraction integrates well with dynamic programming algorithms, and hence it can be applied during structure prediction rather than afterwards. This avoids exponential explosion and can still give us a non-heuristic and complete account of properties of the molecule's folding space.

======== ===========
Home     http://bibiserv.techfak.uni-bielefeld.de/rnashapes
Versions 2.1.6
License  
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/rnashapes/2.1.6
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install rnashapes

and update with::

   conda update rnashapes


