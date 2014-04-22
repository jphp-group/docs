String Type
-----------

A string is series of characters, where a character is the same as 2 bytes.
This means that JPHP supports native unicode strings. See details of the string type.

.. warning::

  JPHP uses a special internal type for binary strings (where a character is the same as 1 byte).


Single quoted
*************

The simplest way to specify a string is to enclose it in single quotes (the character ``'``).

To specify a literal single quote, escape it with a backslash (``\``).
To specify a literal backslash, double it (``\\``). All other instances of backslash will be
treated as a literal backslash: this means that the other escape sequences you might be used to,
such as ``\r`` or ``\n``, will be output literally as specified rather than having any special meaning.

.. note::

  Unlike the double-quoted and heredoc syntaxes, variables and escape sequences for special characters will
  not be expanded when they occur in single quoted strings.

.. code-block:: php

  echo 'this is a simple string';

  echo 'You can also have embedded newlines in
  strings this way as it is
  okay to do';

  // Outputs: Arnold once said: "I'll be back"
  echo 'Arnold once said: "I\'ll be back"';

  // Outputs: You deleted C:\*.*?
  echo 'You deleted C:\\*.*?';

  // Outputs: You deleted C:\*.*?
  echo 'You deleted C:\*.*?';

  // Outputs: This will not expand: \n a newline
  echo 'This will not expand: \n a newline';

  // Outputs: Variables do not $expand $either
  echo 'Variables do not $expand $either';

Double quoted
*************

If the string is enclosed in double-quotes (``"``), JPHP will interpret more escape sequences for special characters:

**Escaped characters**

==================  =================================================================================================
Sequence            Meaning
==================  =================================================================================================
\n 	                linefeed (LF or 0x0A (10) in ASCII)
\r 	                carriage return (CR or 0x0D (13) in ASCII)
\t      	          horizontal tab (HT or 0x09 (9) in ASCII)
\v      	          vertical tab (VT or 0x0B (11) in ASCII) (since PHP 5.2.5)
\e 	                escape (ESC or 0x1B (27) in ASCII) (since PHP 5.4.0)
\f 	                form feed (FF or 0x0C (12) in ASCII) (since PHP 5.2.5)
\\ 	                backslash
\$ 	                dollar sign
\" 	                double-quote
\[0-7]{1,3} 	      the sequence of characters matching the regular expression is a character in octal notation
\x[0-9A-Fa-f]{1,4} 	the sequence of characters matching the regular expression is a character in hexadecimal notation
==================  =================================================================================================

As in single quoted strings, escaping any other character will result in the backslash being printed too.

The most important feature of double-quoted strings is the fact that variable names will be expanded.
See string parsing for details.
