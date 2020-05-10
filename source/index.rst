.. anuar-sphinx-test documentation master file, created by
   sphinx-quickstart on Sat May  9 13:37:20 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to anuar-sphinx-test's documentation!
=============================================

.. toctree::
   :maxdepth: 4
   :caption: Contents:

   tutorials/tutorial1

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


A Subpoint
----------
This is my idea.

A subsubpoint
+++++++++++++
This is a smaller idea.

COMPLEX TABLE:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

SIMPLE TABLE:

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

.. figure::  images/sweat.jpg
   :align:   center
   
   
This is a statement.

.. warning::

   Never, ever, use this code!

.. versionadded:: 0.0.1

It's okay to use this code.

   Proof that getting rich is mostly luck.
   
 Here is something I want to talk about::

    def my_fn(foo, bar=True):
        """A really useful function.

        Returns None
        """

