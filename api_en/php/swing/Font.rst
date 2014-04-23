Font
--------------

.. include:: /api_en.desc/php/swing/Font.header.rst

.. php:class:: php\\swing\\Font



**Properties**

----------

 .. php:attr:: family

  :doc:`string </api_en/.types/string>`

  **read-only**


  Family name of font

 .. php:attr:: fontName

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: name

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: psName

  :doc:`string </api_en/.types/string>`

  **read-only**


  PostScript name of font

 .. php:attr:: size

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: size2D

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: style

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: italicAngle

  :doc:`double </api_en/.types/double>`

  **read-only**


 .. php:attr:: attributes

  :doc:`string[] </api_en/.types/string>`

  **read-only**


 .. php:attr:: numGlyphs

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($name, $style, $size)

  :param $name: 
  :param $style: :doc:`int </api_en/.types/int>` - PLAIN, BOLD, ITALIC
  :param $size: 

 .. php:method:: isBold()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isItalic()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isPlain()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isTransformed()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getBaselineFor($symbol)

  :param $symbol: :doc:`string </api_en/.types/string>` - one char
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: canDisplay($symbol)

  :param $symbol: :doc:`string </api_en/.types/string>` - one char
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: canDisplayUpTo($string)

  Indicates whether or not this Font can display a specified String.

  :param $string: 
  :returns: :doc:`int </api_en/.types/int>` - an offset into $string that points to the first character in $string that this
  Font cannot display; or -1 if this Font can display all characters in $string.

 .. php:staticmethod:: decode($str)

  Decode font by using a specified string

  :param $str: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>` 

 .. php:staticmethod:: create($source, $trueType = true)

  Create new font by using Stream or File

  :param $source: 
  :param $trueType: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>` 

 .. php:staticmethod:: get($name)

  Get font by name

  :param $name: 
  :returns: :doc:`php\\swing\\Font </api_en/php/swing/Font>`, :doc:`null </api_en/.types/null>` - return null if not exists



.. include:: /api_en.desc/php/swing/Font.footer.rst

