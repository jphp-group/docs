Double Type
-----------

Floating point numbers (also known as "floats", "doubles", or "real numbers")
can be specified using any of the following syntaxes:

.. code-block:: php

  <?php
  $a = 1.234;
  $b = 1.2e3;
  $c = 7E-10;
  ?>

Formally::

  LNUM          [0-9]+
  DNUM          ([0-9]*[\.]{LNUM}) | ({LNUM}[\.][0-9]*)
  EXPONENT_DNUM [+-]?(({LNUM} | {DNUM}) [eE][+-]? {LNUM})


.. note::

  In JPHP float point numbers is always the java ``double`` type (2 word number or 64bit).
