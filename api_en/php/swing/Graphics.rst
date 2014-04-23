Graphics
------------------

.. include:: /api_en.desc/php/swing/Graphics.header.rst

.. php:class:: php\\swing\\Graphics

 Class Graphics



**Properties**

----------

 .. php:attr:: color

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

  Foreground color

 .. php:attr:: font

  :doc:`php\\swing\\Font </api_en/php/swing/Font>`

  Font of text



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: getTextWidth($str)

  Return width of str for drawText + current font

  :param $str: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getTextHeight()

  Return height of one line text with current font

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setPaintMode()


 .. php:method:: drawLine($x1, $y1, $x2, $y2)

  Draw line

  :param $x1: 
  :param $y1: 
  :param $x2: 
  :param $y2: 

 .. php:method:: drawRect($x, $y, $width, $height)

  Draw rect

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: fillRect($x, $y, $width, $height)

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: draw3DRect($x, $y, $width, $height, $raised)

  Draws a 3-D highlighted outline of the specified rectangle.

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 
  :param $raised: 

 .. php:method:: fill3DRect($x, $y, $width, $height, $raised)

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 
  :param $raised: 

 .. php:method:: drawOval($x, $y, $width, $height)

  Draw oval

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: fillOval($x, $y, $width, $height)

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: drawArc($x, $y, $width, $height, $startAngle, $arcAngle)

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 
  :param $startAngle: 
  :param $arcAngle: 

 .. php:method:: fillArc($x, $y, $width, $height, $startAngle, $arcAngle)

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 
  :param $startAngle: 
  :param $arcAngle: 

 .. php:method:: drawPolygon($xy)

  :param $xy: :doc:`array </api_en/.types/array>` - [[x1, y1], [x2, y2], ... ]

 .. php:method:: fillPolygon($xy)

  :param $xy: :doc:`array </api_en/.types/array>` - [[x1, y1], [x2, y2], ... ]

 .. php:method:: drawPolyline($xy)

  :param $xy: :doc:`array </api_en/.types/array>` - [[x1, y1], [x2, y2], ... ]

 .. php:method:: drawImage($image, $x = 0, $y = 0, $newWidth = null, $newHeight = null)

  :param $image: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 
  :param $x: 
  :param $y: 
  :param $newWidth: 
  :param $newHeight: 

 .. php:method:: drawText($text, $x, $y)

  :param $text: 
  :param $x: 
  :param $y: 

 .. php:method:: clipRect($x, $y, $width, $height)

  Intersects the current clip with the specified rectangle.

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: clearRect($x, $y, $width, $height)

  Clears the specified rectangle by filling it with the background
  color of the current drawing surface.

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 

 .. php:method:: setXORMode($color)

  :param $color: 

 .. php:method:: translate($x, $y)

  Translates the origin of the graphics context to the point
  (x, y) in the current coordinate system.

  :param $x: 
  :param $y: 

 .. php:method:: copyArea($x, $y, $width, $height, $dx, $dy)

  Copies an area of the component by a distance specified by
  $dx and $dy

  :param $x: 
  :param $y: 
  :param $width: 
  :param $height: 
  :param $dx: 
  :param $dy: 

 .. php:method:: create($x = null, $y = null, $w = null, $h = null)

  Create new copy Graphics from this

  :param $x: 
  :param $y: 
  :param $w: 
  :param $h: 
  :returns: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: dispose()




.. include:: /api_en.desc/php/swing/Graphics.footer.rst

