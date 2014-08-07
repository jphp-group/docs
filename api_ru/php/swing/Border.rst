Border
----------------

.. include:: /api_ru.desc/php/swing/Border.header.rst

.. php:class:: php\\swing\\Border

 Class Border



**Methods**

----------

 .. php:method:: isOpaque()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: createEmpty($top, $left, $bottom, $right)

  :param $top: :doc:`int </api_ru/.types/int>` 
  :param $left: :doc:`int </api_ru/.types/int>` 
  :param $bottom: :doc:`int </api_ru/.types/int>` 
  :param $right: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createBevel($type, $highlightColor, $shadowColor)

  :param $type: :doc:`string </api_ru/.types/string>`  - - RAISED or LOWERED
  :param $highlightColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :param $shadowColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createSoftBevel($type, $highlightColor, $shadowColor)

  :param $type: :doc:`string </api_ru/.types/string>`  - - RAISED or LOWERED
  :param $highlightColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :param $shadowColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createEtchedBevel($type, $highlightColor, $shadowColor)

  :param $type: :doc:`string </api_ru/.types/string>`  - - RAISED or LOWERED
  :param $highlightColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :param $shadowColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createTitled($title, $border = null, $titleFont = null, $titleColor = null)

  :param $title: :doc:`string </api_ru/.types/string>` 
  :param $border: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 
  :param $titleFont: :doc:`php\\swing\\Font </api_ru/php/swing/Font>` 
  :param $titleColor: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createLine($color, $size = 1, $rounded = false)

  :param $color: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :param $size: :doc:`int </api_ru/.types/int>` 
  :param $rounded: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 

 .. php:staticmethod:: createDashed($color, $thickness = 1, $length = 2, $spacing = 1, $rounded = false)

  :param $color: :doc:`php\\swing\\Color </api_ru/php/swing/Color>`, :doc:`array </api_ru/.types/array>`, :doc:`int </api_ru/.types/int>` 
  :param $thickness: :doc:`int </api_ru/.types/int>` 
  :param $length: :doc:`int </api_ru/.types/int>` 
  :param $spacing: :doc:`int </api_ru/.types/int>` 
  :param $rounded: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`php\\swing\\Border </api_ru/php/swing/Border>` 



.. include:: /api_ru.desc/php/swing/Border.footer.rst

