Lists
=====

Lists are collections of scalars. There are typed lists called vectors and jeneric ones.

If several numbers have spaces separating them, they form a list:

::

  o)2 78 3
  2 78 3

Symbols work the same way, but the spaces are optional:

::

  o)`bread `apples `soap
  `bread`apples`soap

Boolean lists are suffixed with b and require no spaces between elements:

::

  o)10010b
  1 0 0 1 0

Generic lists are enclosed in () and each element should be separated by a semicolon:

::

  o)(1 2 3;"food";`b)
  1 2 3
  "food"
  `b

