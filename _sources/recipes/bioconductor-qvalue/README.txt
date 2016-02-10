.. _`bioconductor-qvalue`:

bioconductor-qvalue
===================

This package takes a list of p-values resulting from the simultaneous testing of many hypotheses and estimates their q-values and local FDR values. The q-value of a test measures the proportion of false positives incurred (called the false discovery rate) when that particular test is called significant. The local FDR measures the posterior probability the null hypothesis is true given the test's p-value. Various plots are automatically generated, allowing one to make sensible significance cut-offs. Several mathematical results have recently been shown on the conservative accuracy of the estimated q-values from this software. The software can be applied to problems in genomics, brain imaging, astrophysics, and data mining.

======== ===========
Home     http://bioconductor.org/packages/release/bioc/html/qvalue.html
Versions 2.2.2
License  LGPL
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qvalue
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install bioconductor-qvalue

and update with::

   conda update bioconductor-qvalue


