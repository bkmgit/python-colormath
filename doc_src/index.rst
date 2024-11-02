.. _index:

.. include:: global.txt

python-colormath2
================

python-colormath2 is a simple Python module that spares the user from directly
dealing with
`color math <http://www.brucelindbloom.com/index.html?Eqn_DeltaE_CMC.html>`_.
Some features include:

* Support for a wide range of color spaces. A good chunk of the CIE spaces,
  RGB, HSL/HSV, CMY/CMYK, and many more.
* :doc:`Conversions <conversions>` between the various color spaces.
  For example, XYZ to sRGB, Spectral to XYZ, CIE Lab to Adobe RGB.
* Calculation of :doc:`color difference <delta_e>`. All CIE Delta E functions,
  plus CMC.
* Chromatic adaptations (changing illuminants).
* RGB to hex and vice-versa.
* 16-bit RGB support.
* Runs Python 3.7+.

**License:** python-colormath2 is licensed under the `3 Clause BSD License`_.

Assorted Info
-------------

* `Issue tracker`_ - Report bugs, ask questions, and share ideas here.
* `GitHub project`_ - Source code and issue tracking.

Topics
------

.. toctree::
   :maxdepth: 2

   installation
   color_objects
   illuminants
   conversions
   delta_e
   density
   color_appearance_models

.. toctree::
   :maxdepth: 1

   release_notes

Useful color math resources
---------------------------

* `Bruce Lindbloom`_ - Lots of formulas, calculators, and standards.
* `John the Math Guy`_ - Useful tutorials and explanations of color theory.

.. _Bruce Lindbloom: http://www.brucelindbloom.com/
.. _John the Math Guy: http://johnthemathguy.blogspot.com/
