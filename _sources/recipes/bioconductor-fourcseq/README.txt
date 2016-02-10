.. _`bioconductor-fourcseq`:

bioconductor-fourcseq
=====================

FourCSeq is an R package dedicated to the analysis of (multiplexed) 4C sequencing data. The package provides a pipeline to detect specific interactions between DNA elements and identify differential interactions between conditions. The statistical analysis in R starts with individual bam files for each sample as inputs. To obtain these files, the package contains a python script (extdata/python/demultiplex.py) to demultiplex libraries and trim off primer sequences. With a standard alignment software the required bam files can be then be generated.

======== ===========
Home     http://bioconductor.org/packages/release/bioc/html/FourCSeq.html
Versions 1.4.0
License  GPL (>= 3)
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fourcseq
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install bioconductor-fourcseq

and update with::

   conda update bioconductor-fourcseq


