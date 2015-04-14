Polyline
---------------------

.. include:: /api_ru.desc/php/gdx/math/Polyline.header.rst

.. php:class:: php\\gdx\\math\\Polyline

 Class Polyline



**Methods**

----------

 .. php:method:: __construct($vertices)

  :param $vertices: :doc:`array </api_ru/.types/array>`  - (optional)

 .. php:method:: getVertices()

  Returns the polyline's local vertices without scaling or rotation and without being offset by the polyline position.

  :returns: :doc:`float[] </api_ru/.types/float>` 

 .. php:method:: getTransformedVertices()

  :returns: :doc:`float[] </api_ru/.types/float>` vertices scaled, rotated, and offset by the polyline position.

 .. php:method:: getLength()

  :returns: :doc:`float </api_ru/.types/float>` Returns the euclidean length of the polyline without scaling

 .. php:method:: getScaledLength()

  :returns: :doc:`float </api_ru/.types/float>` Returns the euclidean length of the polyline

 .. php:method:: calculateLength()


 .. php:method:: calculateScaledLength()


 .. php:method:: dirty()


 .. php:method:: setOrigin($originX, $originY)

  Sets the origin point to which all of the polyline's local vertices are relative to.

  :param $originX: :doc:`float </api_ru/.types/float>` 
  :param $originY: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setPosition($x, $y)

  Sets the polyline's position within the world.

  :param $x: :doc:`float </api_ru/.types/float>` 
  :param $y: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setVertices($vertices)

  :param $vertices: :doc:`array </api_ru/.types/array>` 

 .. php:method:: translate($x, $y)

  Translates the polyline's position by the specified horizontal and vertical amounts.

  :param $x: :doc:`float </api_ru/.types/float>` 
  :param $y: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setRotation($degrees)

  Sets the polyline to be rotated by the supplied degrees.

  :param $degrees: :doc:`float </api_ru/.types/float>` 

 .. php:method:: rotate($degrees)

  Applies additional rotation to the polyline by the supplied degrees.

  :param $degrees: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setScale($scaleX, $scaleY)

  Sets the amount of scaling to be applied to the polyline.

  :param $scaleX: :doc:`float </api_ru/.types/float>` 
  :param $scaleY: :doc:`float </api_ru/.types/float>` 

 .. php:method:: scale($amount)

  Applies additional scaling to the polyline by the supplied amount.

  :param $amount: :doc:`float </api_ru/.types/float>` 

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



.. include:: /api_ru.desc/php/gdx/math/Polyline.footer.rst

