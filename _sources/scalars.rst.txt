Scalars
=======

- Numbers are composed of digits and can optionally have a leading negative sign or decimal part.

- Characters are enclosed in double quotes (") and can make use of the escape sequences \n, \t, \" or \\ to produce a newline, tab, double quote or backslash character, respectively. If more than one unescaped character is enclosed in quotes, the noun is a list of characters (see below), also known as a string.

- Symbols are start with a backtick (`) and are followed by an optional name. Names must start with . or a letter, and may contain letters, digits or .. Symbols are mainly useful as handles to variable names or keys in dictionaries.

Reference
---------

+-----------+-----+-----------------+-------+
| Type      | Id  | Size (in bytes) | Notes |
+===========+=====+=================+=======+
| BOOL      | -1  | 1               |       |
+-----------+-----+-----------------+-------+
| GUID      | -2  | 8               | NYI   |
+-----------+-----+-----------------+-------+
| INT       | -6  | 4               |       |
+-----------+-----+-----------------+-------+
| LONG      | -7  | 8               |       |
+-----------+-----+-----------------+-------+
| FLOAT     | -9  | 8               |       |
+-----------+-----+-----------------+-------+
| CHAR      | -10 | 1               |       |
+-----------+-----+-----------------+-------+
| SYMBOL    | -11 | 8               |       |
+-----------+-----+-----------------+-------+
| TIMESTAMP | -12 | 8               | NYI   |
+-----------+-----+-----------------+-------+
| MONTH     | -13 | 4               | NYI   |
+-----------+-----+-----------------+-------+
| DATE      | -14 | 4               | NYI   |
+-----------+-----+-----------------+-------+
| DATETIME  | -15 | 8               | NYI   |
+-----------+-----+-----------------+-------+
| TIMESPAN  | -16 | 8               | NYI   |
+-----------+-----+-----------------+-------+
| MINUTE    | -17 | 4               | NYI   |
+-----------+-----+-----------------+-------+
| SECOND    | -18 | 4               | NYI   |
+-----------+-----+-----------------+-------+
| TIME      | -19 | 8               | NYI   |
+-----------+-----+-----------------+-------+
