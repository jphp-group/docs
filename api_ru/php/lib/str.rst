str
-----------

.. include:: /api_ru.desc/php/lib/str.header.rst

.. php:class:: php\\lib\\str

 Class str



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: ord($char)

  :param $char: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: char($code)

  :param $code: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: pos($string, $search, $fromIndex = 0)

  Returns the index within this string of the first occurrence of the
  specified substring, starting at the specified index.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $search: :doc:`string </api_ru/.types/string>`  - the substring to search for
  :param $fromIndex: :doc:`int </api_ru/.types/int>`  - the index from which to start the search.
  :returns: :doc:`int </api_ru/.types/int>` - returns -1 if not found

 .. php:staticmethod:: posIgnoreCase($string, $search, $fromIndex = 0)

  The same method as ``pos()`` only with ignoring case characters

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $search: :doc:`string </api_ru/.types/string>`  - the substring to search for.
  :param $fromIndex: :doc:`int </api_ru/.types/int>`  - the index from which to start the search.
  :returns: :doc:`int </api_ru/.types/int>` - returns -1 if not found

 .. php:staticmethod:: lastPos($string, $search, $fromIndex = null)

  Returns the index within this string of the last occurrence of the
  specified substring. The last occurrence of the empty string ""
  is considered to occur at the index value ``$string.length``.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $search: :doc:`string </api_ru/.types/string>`  - the substring to search for.
  :param $fromIndex: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>`  - - null means $fromIndex will be equal $string.length
  :returns: :doc:`int </api_ru/.types/int>` - returns -1 if not found

 .. php:staticmethod:: lastPosIgnoreCase($string, $search, $fromIndex = null)

  The same method as ``lastPos()`` only with ignoring case characters

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $search: :doc:`string </api_ru/.types/string>`  - the substring to search for.
  :param $fromIndex: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>`  - - null means $fromIndex will be equal $string.length
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: sub($string, $beginIndex, $endIndex = null)

  Returns a new string that is a substring of this string. The
  substring begins at the specified ``$beginIndex`` and
  extends to the character at index ``$endIndex`` - 1.
  Thus the length of the substring is ``endIndex - beginIndex``.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $beginIndex: :doc:`int </api_ru/.types/int>` 
  :param $endIndex: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>`  - When ``$endIndex`` equals to ``null`` then it will be equal ``$string.length``
  :returns: :doc:`string </api_ru/.types/string>` - return false if params are invalid

 .. php:staticmethod:: compare($string1, $string2)

  Compares two strings lexicographically.
  The comparison is based on the Unicode value of each character in
  the strings.
  
  The character sequence represented by ``$string1``
  ``String`` is compared lexicographically to the
  character sequence represented by ``$string2``. The result is
  a negative integer if ``$string1``
  lexicographically precedes ``$string2``. The result is a
  positive integer if ``$string1`` lexicographically
  follows ``$string2``. The result is zero if the strings
  are equal; ``compare`` returns **0** exactly when
  the strings are equal

  :param $string1: :doc:`string </api_ru/.types/string>`  - - first string
  :param $string2: :doc:`string </api_ru/.types/string>`  - - second string
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: compareIgnoreCase($string1, $string2)

  The same method as ``compare()`` only with ignoring case characters

  :param $string1: :doc:`string </api_ru/.types/string>` 
  :param $string2: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: equalsIgnoreCase($string1, $string2)

  Checks that the strings are equal with ignoring case characters

  :param $string1: :doc:`string </api_ru/.types/string>` 
  :param $string2: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: startsWith($string, $prefix, $offset = 0)

  Tests if the substring of this string beginning at the
  specified index starts with the specified prefix.
  
  Returns ```true`` if the character sequence represented by the
  argument is a prefix of the substring of this object starting
  at index ``offset``; ``false`` otherwise.
  The result is ``false`` if ``toffset`` is
  negative or greater than the length of this
  ``$string``; otherwise the result is the same
  as the result of the expression
  
  .. code-block:: php
  
  startsWith(sub($offset), $prefix)

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $prefix: :doc:`string </api_ru/.types/string>` 
  :param $offset: :doc:`int </api_ru/.types/int>`  - where to begin looking in this string
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: endsWith($string, $suffix)

  Tests if this string ends with the specified suffix.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $suffix: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: lower($string)

  Converts all of the characters in ``$string`` to lower
  case using the rules of the default locale.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: upper($string)

  Converts all of the characters in ``$string`` to upper
  case using the rules of the default locale.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: length($string)

  Returns the length of ``$string``.
  The length is equal to the number of `Unicode code units` in the string.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: replace($string, $target, $replacement)

  Replaces each substring of this string that matches the literal target
  sequence with the specified literal replacement sequence. The
  replacement proceeds from the beginning of the string to the end, for
  example, replacing "aa" with "b" in the string "aaa" will result in
  "ba" rather than "ab".

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $target: :doc:`string </api_ru/.types/string>`  - The sequence of char values to be replaced
  :param $replacement: :doc:`string </api_ru/.types/string>`  - The replacement sequence of char values
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: repeat($string, $amount)

  Return s a new string consisting of the original ``$string`` repeated

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $amount: :doc:`int </api_ru/.types/int>`  - number of times to repeat str
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: trim($string)

  Returns a copy of the string, with leading and trailing whitespace
  omitted.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: reverse($string)

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: shuffle($string)

  Returns a randomized string based on chars in $string

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: split($string, $separator, $limit = 0)

  The method like ``explode()`` in Zend PHP

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $separator: :doc:`string </api_ru/.types/string>` 
  :param $limit: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: join($iterable, $separator, $limit = 0)

  The method like ``implode()`` in Zend PHP

  :param $iterable: :doc:`array </api_ru/.types/array>`, :doc:`php\\lib\\\\Iterator </api_ru/php/lib//Iterator>` 
  :param $separator: :doc:`string </api_ru/.types/string>` 
  :param $limit: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`string </api_ru/.types/string>` 



.. include:: /api_ru.desc/php/lib/str.footer.rst

