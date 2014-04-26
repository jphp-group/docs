Font
--------------

.. include:: /api_ru.desc/php/swing/Font.header.rst

.. php:class:: php\\swing\\Font



**Constants**

----------

 .. php:const:: PLAIN

 .. php:const:: BOLD

 .. php:const:: ITALIC



**Properties**

----------

 .. php:attr:: family

  :doc:`string </api_ru/.types/string>`

  **read-only**


  Family name of font

 .. php:attr:: fontName

  :doc:`string </api_ru/.types/string>`

  **read-only**


 .. php:attr:: name

  :doc:`string </api_ru/.types/string>`

  **read-only**


 .. php:attr:: psName

  :doc:`string </api_ru/.types/string>`

  **read-only**


  PostScript name of font

 .. php:attr:: size

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: size2D

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: style

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: italicAngle

  :doc:`double </api_ru/.types/double>`

  **read-only**


 .. php:attr:: attributes

  :doc:`string[] </api_ru/.types/string>`

  **read-only**


 .. php:attr:: numGlyphs

  :doc:`int </api_ru/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($name, $style, $size)

  :param $name: :doc:`string </api_ru/.types/string>` 
  :param $style: :doc:`int </api_ru/.types/int>`  - - PLAIN, BOLD, ITALIC
  :param $size: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isBold()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isItalic()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isPlain()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isTransformed()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getBaselineFor($symbol)

  :param $symbol: :doc:`string </api_ru/.types/string>`  - - one char
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: canDisplay($symbol)

  :param $symbol: :doc:`string </api_ru/.types/string>`  - - one char
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: canDisplayUpTo($string)

  Indicates whether or not this Font can display a specified String.

  :param $string: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`int </api_ru/.types/int>` - an offset into $string that points to the first character in $string that this
  Font cannot display; or -1 if this Font can display all characters in $string.

 .. php:staticmethod:: decode($str)

  Decode font by using a specified string

  :param $str: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\swing\\Font </api_ru/php/swing/Font>` 

 .. php:staticmethod:: create($source, $trueType = true)

  Create new font by using Stream or File

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  **throws** :doc:`php\\swing\\\\Exception </api_ru/php/swing//Exception>`

  :param $source: :doc:`string </api_ru/.types/string>`, :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 
  :param $trueType: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`php\\swing\\Font </api_ru/php/swing/Font>` 

 .. php:staticmethod:: get($name)

  Get font by name

  :param $name: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\swing\\Font </api_ru/php/swing/Font>`, :doc:`null </api_ru/.types/null>` - return null if not exists



.. include:: /api_ru.desc/php/swing/Font.footer.rst

