.. _`r-r.methodss3`:

r-r.methodss3
=============

Methods that simplify the setup of S3 generic functions and S3 methods.  Major effort has been made in making definition of methods as simple as possible with a minimum of maintenance for package developers.  For example, generic functions are created automatically, if missing, and naming conflict are automatically solved, if possible.  The method setMethodS3() is a good start for those who in the future may want to migrate to S4.  This is a cross-platform package implemented in pure R that generates standard S3 methods.

======== ===========
Home     
Versions 1.7.0
License  LGPL (>= 2.1)
Recipe   https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-r.methodss3
======== ===========

Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`setup`), install with::

   conda install r-r.methodss3

and update with::

   conda update r-r.methodss3


