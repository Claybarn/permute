Permutation tests and confidence sets
=====================================

.. note::

   ``permute-multitest`` is a fork of `statlab/permute <https://github.com/statlab/permute>`_
   maintained by Clayton Barnes. It adds multi-test versions of the permutation tests
   (``permute.multitest_core`` and ``permute.multitest_stratified``) that test many
   hypotheses, such as every time point or channel, against one shared permutation
   distribution. The import name is still ``permute``, so it can't be installed
   alongside statlab's package. The original authors are credited below.

|PyPI| |Build Status| |Coverage Status|

Permutation tests and confidence sets for a variety of nonparametric
testing and estimation problems, for a variety of randomization designs.

-  **Website (including documentation):**
   http://statlab.github.io/permute
-  **Mailing list:** http://groups.google.com/group/permute
-  **Source:** https://github.com/statlab/permute
-  **Bug reports:** https://github.com/statlab/permute/issues

Installation from binaries
--------------------------

::

   $ pip install permute

Installation from source
------------------------

Install dependencies using:

::

   $ pip install -r requirements.txt

Then, install permute using:

::

   $ pip install .

If you plan to develop the package, you may run it directly from source:

::

   $ pip install -e .       # Do this once to add pkg to Python path

License information
-------------------

See the file LICENSE for information on the history of this software,
terms & conditions for usage, and a DISCLAIMER OF ALL WARRANTIES.

.. |PyPI| image:: https://img.shields.io/pypi/v/permute.svg
   :target: https://pypi.org/project/permute/
.. |Build Status| image:: https://github.com/statlab/permute/workflows/default/badge.svg?branch=master
   :target: https://github.com/statlab/permute/actions?query=workflow%3Adefault+branch%3Amaster
.. |Coverage Status| image:: https://codecov.io/gh/statlab/permute/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/statlab/permute
