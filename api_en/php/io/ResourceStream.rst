ResourceStream
---------------------

.. php:class:: php\\io\\ResourceStream

 **extends**: :doc:`php\\io\\Stream </api_en/php/io/Stream>`


 Class ResourceStream

 .. php:method:: __construct($path)

  :param $path: 

 .. php:method:: read($length)

  :param $length: :doc:`int </api_en/.types/int>` - count of bytes
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: readFully()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  :param $value: 
  :param $length: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: seek($position)

  :param $position: 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getPosition()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

