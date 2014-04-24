Image
---------------

.. include:: /api_en.desc/php/swing/Image.header.rst

.. php:class:: php\\swing\\Image



**Constants**

----------

 .. php:const:: TYPE_INT_RGB

 .. php:const:: TYPE_INT_ARGB

 .. php:const:: TYPE_INT_ARGB_PRE

 .. php:const:: TYPE_INT_BGR

 .. php:const:: TYPE_3BYTE_BGR

 .. php:const:: TYPE_4BYTE_ABGR

 .. php:const:: TYPE_4BYTE_ABGR_PRE

 .. php:const:: TYPE_USHORT_565_RGB

 .. php:const:: TYPE_USHORT_555_RGB

 .. php:const:: TYPE_BYTE_GRAY

 .. php:const:: TYPE_USHORT_GRAY

 .. php:const:: TYPE_BYTE_BINARY

 .. php:const:: TYPE_BYTE_INDEXED



**Properties**

----------

 .. php:attr:: type

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: width

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: height

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($width, $height, $type = ::)

  :param $width: :doc:`int </api_en/.types/int>` 
  :param $height: :doc:`int </api_en/.types/int>` 
  :param $type: :doc:`int </api_en/.types/int>` 

 .. php:method:: getSubimage($x, $y, $w, $h)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :param $w: :doc:`int </api_en/.types/int>` 
  :param $h: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: getRGB($x, $y)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setRGB($x, $y, $rgb)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :param $rgb: :doc:`int </api_en/.types/int>`  - - color

 .. php:method:: getGraphics()

  :returns: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: getProperty($name)

  :param $name: 
  :returns: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>`, :doc:`null </api_en/.types/null>` 

 .. php:staticmethod:: read($stream)

  :param $stream: :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`string </api_en/.types/string>`  - - file path or stream
  :returns: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:staticmethod:: write($image, $format, $stream)

  :param $image: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 
  :param $format: 
  :param $stream: :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`string </api_en/.types/string>`  - - file path or stream



.. include:: /api_en.desc/php/swing/Image.footer.rst

