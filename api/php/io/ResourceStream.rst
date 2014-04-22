ResourceStream
---------------------

.. php:class:: php\\io\\ResourceStream

 **extends**: :doc:`php\\io\\Stream </api/php/io/Stream>`


 Class ResourceStream

 .. php:method:: __construct($path)

  :param $path: 

 .. php:method:: read($length)

  :param $length: :doc:`int </api/int>` - count of bytes
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: readFully()

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: write($value, $length = null)

  :param $value: 
  :param $length: 
  :returns: :doc:`int </api/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: seek($position)

  :param $position: 
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: getPosition()

  :returns: :doc:`int </api/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api/mixed>` 

