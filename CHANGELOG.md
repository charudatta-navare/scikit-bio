scikit-bio changelog
====================

Version 0.1.1-dev (changes since 0.1.1 release go here)
-------------------------------------------------------

* Added new ``bioenv`` and ``mantel`` distance-based statistics to ``skbio.math.stats.distance`` subpackage.
* IDs are now optional when constructing a ``DissimilarityMatrix`` or ``DistanceMatrix`` (monotonically-increasing integers cast as strings are automatically used).
* Added ``DistanceMatrix.permute`` method for randomly permuting rows and columns of a distance matrix.

Version 0.1.1 (2014-05-16)
--------------------------

Fixes to setup.py. This is a pre-alpha release. At this stage, major backwards-incompatible API changes can and will happen.

Version 0.1.0 (2014-05-15)
--------------------------

Initial pre-alpha release. At this stage, major backwards-incompatible API changes can and will happen.
