Polygon
--------------------

.. include:: /api_ru.desc/php/gdx/math/Polygon.header.rst

.. php:class:: php\\gdx\\math\\Polygon

 Class Polygon



**Methods**

----------

 .. php:method:: __construct($vertices)

  :param $vertices: :doc:`array </api_ru/.types/array>`  - (optional)

 .. php:method:: getVertices()

  Returns the polygon's local vertices without scaling or rotation and without being offset by the polygon position.

  :returns: :doc:`float[] </api_ru/.types/float>` 

 .. php:method:: getTransformedVertices()

  :returns: :doc:`float[] </api_ru/.types/float>` vertices scaled, rotated, and offset by the polygon position.

 .. php:method:: setOrigin($originX, $originY)

  Sets the origin point to which all of the polygon's local vertices are relative to.

  :param $originX: :doc:`float </api_ru/.types/float>` 
  :param $originY: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setPosition($x, $y)

  Sets the polygon's position within the world.

  :param $x: :doc:`float </api_ru/.types/float>` 
  :param $y: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setVertices($vertices)

  :param $vertices: :doc:`array </api_ru/.types/array>` 

 .. php:method:: translate($x, $y)

  Translates the polygon's position by the specified horizontal and vertical amounts.

  :param $x: :doc:`float </api_ru/.types/float>` 
  :param $y: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setRotation($degrees)

  Sets the polygon to be rotated by the supplied degrees.

  :param $degrees: :doc:`float </api_ru/.types/float>` 

 .. php:method:: rotate($degrees)

  Applies additional rotation to the polygon by the supplied degrees.

  :param $degrees: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setScale($scaleX, $scaleY)

  Sets the amount of scaling to be applied to the polygon.

  :param $scaleX: :doc:`float </api_ru/.types/float>` 
  :param $scaleY: :doc:`float </api_ru/.types/float>` 

 .. php:method:: scale($amount)

  Applies additional scaling to the polygon by the supplied amount.

  :param $amount: :doc:`float </api_ru/.types/float>` 

 .. php:method:: dirty()


 .. php:method:: area()

  Returns the area contained within the polygon.

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: contains($x, $y)

  :param $x: :doc:`float </api_ru/.types/float>` 
  :param $y: :doc:`float </api_ru/.types/float>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getX()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getY()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getOriginX()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getOriginY()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getRotation()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getScaleX()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: getScaleY()

  :returns: :doc:`float </api_ru/.types/float>` 



.. include:: /api_ru.desc/php/gdx/math/Polygon.footer.rst

