.. _`fastq-join`:

fastq-join
==========

Similar to audy's stitch program, but in C, more efficient and supports some automatic benchmarking and tuning. It uses the same "squared distance for anchored alignment" as other tools.

======== ===========
Home     https://github.com/brwnj/fastq-join
Versions 1.3.1
License  MIT
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/fastq-join
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install fastq-join

and update with::

   conda update fastq-join


