Image
---------------

.. php:class:: php\\swing\\Image

 .. php:method:: __construct($width, $height, $type = ::)

  :param $width: 
  :param $height: 
  :param $type: 

 .. php:method:: getSubimage($x, $y, $w, $h)

  :param $x: 
  :param $y: 
  :param $w: 
  :param $h: 
  :returns: :doc:`php\\swing\\Image </api/php/swing/Image>` 

 .. php:method:: getRGB($x, $y)

  :param $x: 
  :param $y: 
  :returns: :doc:`int </api/int>` 

 .. php:method:: setRGB($x, $y, $rgb)

  :param $x: 
  :param $y: 
  :param $rgb: :doc:`int </api/int>` - color

 .. php:method:: getGraphics()

  :returns: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: getProperty($name)

  :param $name: 
  :returns: :doc:`php\\lang\\JavaObject </api/php/lang/JavaObject>`, :doc:`null </api/null>` 

 .. php:staticmethod:: read($stream)

  :param $stream: :doc:`php\\io\\Stream </api/php/io/Stream>`, :doc:`php\\io\\File </api/php/io/File>`, :doc:`string </api/string>` - file path or stream
  :returns: :doc:`php\\swing\\Image </api/php/swing/Image>` 

 .. php:staticmethod:: write($image, $format, $stream)

  :param $image: :doc:`php\\swing\\Image </api/php/swing/Image>` 
  :param $format: 
  :param $stream: :doc:`php\\io\\Stream </api/php/io/Stream>`, :doc:`php\\io\\File </api/php/io/File>`, :doc:`string </api/string>` - file path or stream

