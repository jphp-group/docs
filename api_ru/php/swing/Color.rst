Color
---------------

.. include:: /api_ru.desc/php/swing/Color.header.rst

.. php:class:: php\\swing\\Color



**Properties**

----------

 .. php:attr:: rgb

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: alpha

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: red

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: green

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: blue

  :doc:`int </api_ru/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($rgb, $hasAlpha = false)

  :param $rgb: :doc:`int </api_ru/.types/int>` 
  :param $hasAlpha: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: darker()

  Creates a new Color that is a darker version of this

  :returns: :doc:`php\\swing\\Color </api_ru/php/swing/Color>` 

 .. php:method:: brighter()

  Creates a new Color that is a brighter version of this

  :returns: :doc:`php\\swing\\Color </api_ru/php/swing/Color>` 

 .. php:staticmethod:: rgb($r, $g, $b, $alpha = 255)

  :param $r: :doc:`int </api_ru/.types/int>`  - - 0 .. 255
  :param $g: :doc:`int </api_ru/.types/int>`  - - 0 .. 255
  :param $b: :doc:`int </api_ru/.types/int>`  - - 0 .. 255
  :param $alpha: :doc:`int </api_ru/.types/int>`  - - 0 .. 255
  :returns: :doc:`php\\swing\\Color </api_ru/php/swing/Color>` 

 .. php:staticmethod:: floatRgb($r, $g, $b, $alpha = 1.0)

  :param $r: :doc:`double </api_ru/.types/double>`  - - between 0 and 1
  :param $g: :doc:`double </api_ru/.types/double>`  - - between 0 and 1
  :param $b: :doc:`double </api_ru/.types/double>`  - - between 0 and 1
  :param $alpha: :doc:`double </api_ru/.types/double>`  - - between 0 and 1
  :returns: :doc:`php\\swing\\Color </api_ru/php/swing/Color>` 

 .. php:staticmethod:: decode($nm)

  Decode color from a hex string (#RGB, 0xRGB, etc...)

  :param $nm: 
  :returns: :doc:`php\\swing\\Color </api_ru/php/swing/Color>` 



.. include:: /api_ru.desc/php/swing/Color.footer.rst

