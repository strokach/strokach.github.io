.. _`r-fda`:

r-fda
=====

These functions were developed to support functional data analysis as described in Ramsay, J. O. and Silverman, B. W. (2005) Functional Data Analysis. New York: Springer.  They were ported from earlier versions in Matlab and S-PLUS.  An introduction appears in Ramsay, J. O., Hooker, Giles, and Graves, Spencer (2009) Functional Data Analysis with R and Matlab (Springer). The package includes data sets and script files working many examples including all but one of the 76 figures in this latter book.  Matlab versions of the code and sample analyses are no longer distributed through CRAN, as they were when the book was published.  For those, ftp from http://www.psych.mcgill.ca/misc/fda/downloads/FDAfuns/ There you find a set of .zip files containing the functions and sample analyses, as well as two .txt files giving instructions for installation and some additional information. The changes from Version 2.4.1 are fixes of bugs in density.fd and removal of functions create.polynomial.basis, polynompen, and  polynomial. These were deleted because the monomial basis does the same thing and because there were errors in the code.

======== ===========
Home     http://www.functionaldata.org
Versions 2.4.4
License  GPL (>= 2)
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-fda
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-fda

and update with::

   conda update r-fda


