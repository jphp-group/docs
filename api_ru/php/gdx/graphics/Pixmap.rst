Pixmap
-----------------------

.. include:: /api_ru.desc/php/gdx/graphics/Pixmap.header.rst

.. php:class:: php\\gdx\\graphics\\Pixmap

 Class Pixmap



**Methods**

----------

 .. php:method:: __construct($width, $height, $format)

  :param $width: :doc:`int </api_ru/.types/int>` 
  :param $height: :doc:`int </api_ru/.types/int>` 
  :param $format: :doc:`string </api_ru/.types/string>`  - - Alpha, Intensity, LuminanceAlpha, RGB565, RGBA4444, RGB888, RGBA8888

 .. php:staticmethod:: ofFile($fileHandle)

  :param $fileHandle: :doc:`php\\gdx\\files\\FileHandle </api_ru/php/gdx/files/FileHandle>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: setColor($redOrColor, $g, $b, $a)

  :param $redOrColor: :doc:`double </api_ru/.types/double>`, :doc:`int </api_ru/.types/int>` 
  :param $g: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $b: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $a: :doc:`double </api_ru/.types/double>`  - (optional)

 .. php:method:: fill()


 .. php:method:: drawLine($x, $y, $x2, $y2)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $x2: :doc:`int </api_ru/.types/int>` 
  :param $y2: :doc:`int </api_ru/.types/int>` 

 .. php:method:: drawRectangle($x, $y, $width, $height)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $width: :doc:`int </api_ru/.types/int>` 
  :param $height: :doc:`int </api_ru/.types/int>` 

 .. php:method:: drawPixmap($pixmap, $x, $y, $srcx, $srcy, $srcWidth, $srcHeight)

  :param $pixmap: :doc:`php\\gdx\\graphics\\Pixmap </api_ru/php/gdx/graphics/Pixmap>` 
  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $srcx: :doc:`int </api_ru/.types/int>`  - (optional)
  :param $srcy: :doc:`int </api_ru/.types/int>`  - (optional)
  :param $srcWidth: :doc:`int </api_ru/.types/int>`  - (optional)
  :param $srcHeight: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: fillRectangle($x, $y, $width, $height)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $width: :doc:`int </api_ru/.types/int>` 
  :param $height: :doc:`int </api_ru/.types/int>` 

 .. php:method:: drawCircle($x, $y, $radius)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $radius: :doc:`int </api_ru/.types/int>` 

 .. php:method:: fillCircle($x, $y, $radius)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $radius: :doc:`int </api_ru/.types/int>` 

 .. php:method:: fillTriangle($x1, $y1, $x2, $y2, $x3, $y3)

  :param $x1: :doc:`int </api_ru/.types/int>` 
  :param $y1: :doc:`int </api_ru/.types/int>` 
  :param $x2: :doc:`int </api_ru/.types/int>` 
  :param $y2: :doc:`int </api_ru/.types/int>` 
  :param $x3: :doc:`int </api_ru/.types/int>` 
  :param $y3: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getPixel($x, $y)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` The pixel color in RGBA8888 format.

 .. php:method:: getWidth()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getHeight()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: dispose()


 .. php:method:: drawPixel($x, $y, $color)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :param $color: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: getGLFormat()

  :returns: :doc:`int </api_ru/.types/int>` one of GL_ALPHA, GL_RGB, GL_RGBA, GL_LUMINANCE, or GL_LUMINANCE_ALPHA.

 .. php:method:: getGLInternalFormat()

  :returns: :doc:`int </api_ru/.types/int>` one of GL_ALPHA, GL_RGB, GL_RGBA, GL_LUMINANCE, or GL_LUMINANCE_ALPHA.

 .. php:method:: getGLType()

  :returns: :doc:`int </api_ru/.types/int>` one of GL_UNSIGNED_BYTE, GL_UNSIGNED_SHORT_5_6_5, GL_UNSIGNED_SHORT_4_4_4_4

 .. php:method:: getFormat()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getBlending()

  :returns: :doc:`string </api_ru/.types/string>` None, SourceOver

 .. php:staticmethod:: setBlending($blending)

  Sets the type of Blending to be used for all operations. Default is 'SourceOver'

  :param $blending: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: setFilter($filter)

  Filters to be used with Pixmap.drawPixmap(Pixmap, int, int, int, int, int, int, int, int).

  :param $filter: :doc:`string </api_ru/.types/string>`  - NearestNeighbour, BiLinear



.. include:: /api_ru.desc/php/gdx/graphics/Pixmap.footer.rst

