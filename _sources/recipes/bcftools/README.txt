.. _`bcftools`:

bcftools
========

BCFtools is a set of utilities that manipulate variant calls in the Variant Call Format (VCF) and its binary counterpart BCF. All commands work transparently with both VCFs and BCFs, both uncompressed and BGZF-compressed.  Most commands accept VCF, bgzipped VCF and BCF with filetype detected automatically even when streaming from a pipe. Indexed VCF and BCF will work in all situations. Un-indexed VCF and BCF and streams will work in most, but not all situations.

======== ===========
Home     https://github.com/samtools/bcftools
Versions 1.3, 1.2
License  MIT
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bcftools/1.3
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install bcftools

and update with::

   conda update bcftools


