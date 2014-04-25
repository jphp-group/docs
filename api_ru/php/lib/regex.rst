regex
-------------

.. include:: /api_ru.desc/php/lib/regex.header.rst

.. php:class:: php\\lib\\regex

 Utilities for regular expressions
 
 http://www.regular-expressions.info/java.html
 
 Class regex



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: match($pattern, $string)

  Tells whether or not this string matches the given regular expression.
  See also java.lang.String.matches()

  :param $pattern: :doc:`string </api_ru/.types/string>`  - regular expression
  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: split($pattern, $string, $limit = 0)

  Splits this string around matches of the given regular expression.
  See also java.lang.String.split()

  :param $pattern: :doc:`string </api_ru/.types/string>`  - the delimiting regular expression
  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $limit: :doc:`int </api_ru/.types/int>`  - the result threshold
  :returns: :doc:`array </api_ru/.types/array>` the array of strings computed by splitting this string around matches of the given regular expression

 .. php:staticmethod:: quote($string)

  Returns a literal pattern ``String`` for the specified
  ``String``.
  
  
  This method produces a ``String`` that can be used to
  create a ``Pattern`` that would match the string
  ``$string`` as if it were a literal pattern. Metacharacters
  or escape sequences in the input sequence will be given no special
  meaning.

  :param $string: :doc:`string </api_ru/.types/string>`  - The string to be literalized
  :returns: :doc:`string </api_ru/.types/string>` A literal string replacement

 .. php:staticmethod:: quoteReplacement($string)

  Returns a literal replacement ``String`` for the specified
  ``String``.
  
  This method produces a ``String`` that will work
  as a literal replacement $string in the
  replaceWithCallback() method of the ``php\lib\regex\Pattern`` class.
  The ``String`` produced will match the sequence of characters
  in $string treated as a literal sequence. Slashes ('\') and
  dollar signs ('$') will be given no special meaning.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: of($pattern, $string = '', $flag = 0)

  Creates a new Pattern of regex. Alias of php\lib\regex\Pattern::of()

  :param $pattern: :doc:`string </api_ru/.types/string>`  - regular expression
  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $flag: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\lib\\regex\\Pattern </api_ru/php/lib/regex/Pattern>` 



.. include:: /api_ru.desc/php/lib/regex.footer.rst

