Verbs
=====

Verbs are operation primitives each represented as a single character:
  ``+-*%!&|<>=~,^#_$?@.``
Each has different behavior when used as a monad (with one argument) or as a dyad (with two arguments). Verbs can have an additional name for better readibility. For example: ``! --> til``.

Plus
----

Adds two numeric values together:

::

  o)1+2
  3

  o)1+1 2 3
  2 3 4

Minus
-----

Subtracts one numeric value from another:

::

  o)2-1
  1

  o)1 2 3 - 1
  0 1 2

Negate value:

::

  o)-1
  -1

  o)1 2 -3
  1 2 -3
