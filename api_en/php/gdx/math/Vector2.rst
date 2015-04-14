Vector2
--------------------

.. include:: /api_en.desc/php/gdx/math/Vector2.header.rst

.. php:class:: php\\gdx\\math\\Vector2

 Class Vector2



**Methods**

----------

 .. php:method:: __construct($x, $y)

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>`  - (optional)
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)

 .. php:method:: x()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: y()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: len()

  :returns: :doc:`float </api_en/.types/float>` The euclidean length

 .. php:method:: len2()

  :returns: :doc:`float </api_en/.types/float>` The squared euclidean length

 .. php:method:: set($x, $y)

  Sets this vector from the given vector or x, y

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: sub($x, $y)

  Subtracts the given vector from this vector.

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: nor()

  Normalizes this vector. Does nothing if it is zero.

  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: add($x, $y)

  Adds the given vector to this vector

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)

 .. php:method:: dot($ox, $oy)

  :param $ox: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $oy: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`float </api_en/.types/float>` The dot product between this and the other vector

 .. php:method:: scl($x, $y)

  Scales this vector by a scalar

  :param $x: :doc:`float </api_en/.types/float>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: mulAdd($vec, $scalar)

  First scale a supplied vector, then add it to this vector.

  :param $vec: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $scalar: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: dst($x, $y)

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`float </api_en/.types/float>` the distance between this and the other vector

 .. php:method:: dst2($x, $y)

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`float </api_en/.types/float>` the squared distance between this and the other vector

 .. php:method:: limit($limit)

  :param $limit: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: clamp($min, $max)

  :param $min: :doc:`float </api_en/.types/float>` 
  :param $max: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: crs($x, $y)

  :param $x: :doc:`float </api_en/.types/float>`, :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $y: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: angle()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: getAngleRad()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: setAngle($degrees)

  :param $degrees: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: setAngleRad($radians)

  :param $radians: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: rotate($degrees)

  :param $degrees: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: rotateRad($radians)

  :param $radians: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: rotate90($dir)

  :param $dir: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: lerp($target, $alpha)

  Linearly interpolates between this vector and the target vector by alpha which is in the range [0,1]. The result is stored
  in this vector.

  :param $target: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $alpha: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 

 .. php:method:: epsilonEquals($other, $epsilon)

  Compares this vector with the other vector, using the supplied epsilon for fuzzy equality testing.

  :param $other: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $epsilon: :doc:`float </api_en/.types/float>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isUnit($margin)

  Whether this vector is a unit length vector

  :param $margin: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isZero($margin)

  :param $margin: :doc:`float </api_en/.types/float>`  - (optional)

 .. php:method:: isOnLine($other, $epsilon)

  :param $other: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $epsilon: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isCollinear($other, $epsilon)

  :param $other: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $epsilon: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isCollinearOpposite($other, $epsilon)

  :param $other: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $epsilon: :doc:`float </api_en/.types/float>`  - (optional)
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isPerpendicular($vector, $epsilon)

  :param $vector: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :param $epsilon: :doc:`float </api_en/.types/float>`  - (optional)

 .. php:method:: hasSameDirection($vector)

  :param $vector: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: hasOppositeDirection($vector)

  :param $vector: :doc:`php\\gdx\\math\\Vector2 </api_en/php/gdx/math/Vector2>` 
  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/gdx/math/Vector2.footer.rst

