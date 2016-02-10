.. _`r-ggdendro`:

r-ggdendro
==========

This is a set of tools for dendrograms and tree plots using 'ggplot2'.  The 'ggplot2' philosophy is to clearly separate data from the presentation. Unfortunately the plot method for dendrograms plots directly to a plot device without exposing the data. The 'ggdendro' package resolves this by making available functions that extract the dendrogram plot data. The package  provides implementations for tree, rpart, as well as diana and agnes cluster diagrams.

======== ===========
Home     https://github.com/andrie/ggdendro
Versions 0.1_17
License  GPL-2 | GPL-3
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-ggdendro
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-ggdendro

and update with::

   conda update r-ggdendro


