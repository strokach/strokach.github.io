.. _`bioconductor-sva`:

bioconductor-sva
================

The sva package contains functions for removing batch effects and other unwanted variation in high-throughput experiment. Specifically, the sva package contains functions for the identifying and building surrogate variables for high-dimensional data sets. Surrogate variables are covariates constructed directly from high-dimensional data (like gene expression/RNA sequencing/methylation/brain imaging data) that can be used in subsequent analyses to adjust for unknown, unmodeled, or latent sources of noise. The sva package can be used to remove artifacts in three ways: (1) identifying and estimating surrogate variables for unknown sources of variation in high-throughput experiments (Leek and Storey 2007 PLoS Genetics,2008 PNAS), (2) directly removing known batch effects using ComBat (Johnson et al. 2007 Biostatistics) and (3) removing batch effects with known control probes (Leek 2014 biorXiv). Removing batch effects and using surrogate variables in differential expression analysis have been shown to reduce dependence, stabilize error rate estimates, and improve reproducibility, see (Leek and Storey 2007 PLoS Genetics, 2008 PNAS or Leek et al. 2011 Nat. Reviews Genetics).

======== ===========
Home     http://bioconductor.org/packages/release/bioc/html/sva.html
Versions 3.18.0
License  Artistic-2.0
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sva
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install bioconductor-sva

and update with::

   conda update bioconductor-sva


