Scanner
----------------

.. include:: /api_en.desc/php/util/Scanner.header.rst

.. php:class:: php\\util\\Scanner

 **implements**: :doc:`Iterator </api_en/Iterator>`


 A simple text scanner which can parse primitive types and strings using
 regular expressions.
 
 Class Scanner



**Methods**

----------

 .. php:method:: __construct($source, $charset = null)

  **throws** :doc:`php\\lang\\IllegalArgumentException </api_en/php/lang/IllegalArgumentException>` if $charset is invalid

  :param $source: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $charset: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>`  - e.g.: UTF-8, windows-1251, etc., only for Stream objects

 .. php:method:: hasNext($pattern = null)

  :param $pattern: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: next($pattern = null)

  :param $pattern: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 
  :returns: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>` null if doesn't has the next pattern

 .. php:method:: nextLine()

  :returns: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>` null if doesn't has the next line

 .. php:method:: hasNextLine()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: nextInt($radix = null)

  :param $radix: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>`  - if null then uses the default radix
  :returns: :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` null if doesn't has the next int

 .. php:method:: hasNextInt($radix = null)

  :param $radix: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>`  - if null then uses the default radix
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: nextDouble()

  :returns: :doc:`float </api_en/.types/float>`, :doc:`null </api_en/.types/null>` null if does not has the next double

 .. php:method:: hasNextDouble()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: skip($pattern)

  :param $pattern: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 
  :returns: :doc:`bool </api_en/.types/bool>` ``true`` on success, ``false`` on fail

 .. php:method:: useDelimiter($delimiter)

  :param $delimiter: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 
  :returns: :doc:`php\\util\\Scanner </api_en/php/util/Scanner>` 

 .. php:method:: useLocale($locale)

  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 
  :returns: :doc:`php\\util\\Scanner </api_en/php/util/Scanner>` 

 .. php:method:: useRadix($value)

  :param $value: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\util\\Scanner </api_en/php/util/Scanner>` 

 .. php:method:: getIOException()

  Get the last io exception (if does not occur then returns ``null``)

  :returns: :doc:`php\\io\\IOException </api_en/php/io/IOException>`, :doc:`null </api_en/.types/null>` 

 .. php:method:: reset()


 .. php:method:: current()

  Uses the result of the last called ``next()`` method

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: key()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: rewind()


 .. php:method:: __clone()

  **private**





.. include:: /api_en.desc/php/util/Scanner.footer.rst

