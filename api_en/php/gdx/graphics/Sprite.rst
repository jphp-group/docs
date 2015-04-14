Sprite
-----------------------

.. include:: /api_en.desc/php/gdx/graphics/Sprite.header.rst

.. php:class:: php\\gdx\\graphics\\Sprite

 Class Sprite



**Methods**

----------

 .. php:method:: __construct($texture, $width, $height, $x, $y)

  :param $texture: :doc:`php\\gdx\\graphics\\Texture </api_en/php/gdx/graphics/Texture>`  - (optional)
  :param $width: :doc:`int </api_en/.types/int>`  - (optional)
  :param $height: :doc:`int </api_en/.types/int>`  - (optional)
  :param $x: :doc:`int </api_en/.types/int>`  - (optional)
  :param $y: :doc:`int </api_en/.types/int>`  - (optional)

 .. php:method:: setBounds($x, $y, $width, $height)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :param $width: :doc:`int </api_en/.types/int>` 
  :param $height: :doc:`int </api_en/.types/int>` 

 .. php:method:: setSize($width, $height)

  :param $width: :doc:`int </api_en/.types/int>` 
  :param $height: :doc:`int </api_en/.types/int>` 

 .. php:method:: setPosition($x, $y)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 

 .. php:method:: setX($x)

  :param $x: :doc:`int </api_en/.types/int>` 

 .. php:method:: getX()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setY($y)

  :param $y: :doc:`int </api_en/.types/int>` 

 .. php:method:: getY()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: translateX($xAmount)

  :param $xAmount: :doc:`double </api_en/.types/double>` 

 .. php:method:: translateY($yAmount)

  :param $yAmount: :doc:`double </api_en/.types/double>` 

 .. php:method:: translate($xAmount, $yAmount)

  :param $xAmount: :doc:`double </api_en/.types/double>` 
  :param $yAmount: :doc:`double </api_en/.types/double>` 

 .. php:method:: setAlpha($alpha)

  :param $alpha: :doc:`double </api_en/.types/double>` 

 .. php:method:: setOrigin($originX, $originY)

  :param $originX: :doc:`int </api_en/.types/int>` 
  :param $originY: :doc:`int </api_en/.types/int>` 

 .. php:method:: setOriginCenter()


 .. php:method:: setRotation($degrees)

  :param $degrees: :doc:`double </api_en/.types/double>` 

 .. php:method:: getRotation()

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: rotate($degrees)

  :param $degrees: :doc:`double </api_en/.types/double>` 

 .. php:method:: rotate90($clockwise)

  :param $clockwise: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setScale($scaleXY, $scaleY)

  :param $scaleXY: :doc:`double </api_en/.types/double>` 
  :param $scaleY: :doc:`double </api_en/.types/double>`  - (optional)

 .. php:method:: scale($amount)

  :param $amount: :doc:`double </api_en/.types/double>` 

 .. php:method:: flip($x, $y)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 

 .. php:method:: scroll($xAmount, $yAmount)

  :param $xAmount: :doc:`double </api_en/.types/double>` 
  :param $yAmount: :doc:`double </api_en/.types/double>` 

 .. php:method:: draw($batch, $alphaModulation)

  :param $batch: :doc:`php\\gdx\\graphics\\SpriteBatch </api_en/php/gdx/graphics/SpriteBatch>` 
  :param $alphaModulation: :doc:`double </api_en/.types/double>`  - (optional)



.. include:: /api_en.desc/php/gdx/graphics/Sprite.footer.rst

