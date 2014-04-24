char
------------

.. include:: /api_en.desc/php/lib/char.header.rst

.. php:class:: php\\lib\\char

 Char Utils for working with unicode chars
 (using string[0] char)
 
 Class char



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: of($code)

  :param $code: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: ord($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: count($code)

  Determines the number of {@code char} values needed to
  represent the specified character (Unicode code point). If the
  specified character is equal to or greater than 0x10000, then
  the method returns 2. Otherwise, the method returns 1.

  :param $code: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: compare($char1, $char2)

  :param $char1: :doc:`string </api_en/.types/string>` 
  :param $char2: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: lower($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: upper($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: title($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: isSpace($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isDigit($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isLetter($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isLetterOrDigit($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isLower($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isUpper($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isTitle($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isWhitespace($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isISOControl($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isDefined($char)

  Determines if a character is defined in Unicode.

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isMirrored($char)

  Determines whether the specified character (Unicode code point)
  is mirrored according to the Unicode specification.  Mirrored
  characters should have their glyphs horizontally mirrored when
  displayed in text that is right-to-left.

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isLowSurrogate($char)

  Determines if the given $char value is a
  <a href="http://www.unicode.org/glossary/#low_surrogate_code_unit">
  Unicode low-surrogate code unit</a>
  (also known as <i>trailing-surrogate code unit</i>).

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isHighSurrogate($char)

  Determines if the given $char value is a
  <a href="http://www.unicode.org/glossary/#high_surrogate_code_unit">
  Unicode high-surrogate code unit</a>
  (also known as <i>leading-surrogate code unit</i>).

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isPrintable($char)

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: number($char)

  Returns the {@code int} value that the specified Unicode
  character represents.

  :param $char: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`int </api_en/.types/int>` 



.. include:: /api_en.desc/php/lib/char.footer.rst

