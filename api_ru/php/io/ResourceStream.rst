ResourceStream
---------------------

.. php:class:: php\\io\\ResourceStream

 **extends**: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`


 Class ResourceStream

 .. php:method:: __construct($path)

  :param $path: 

 .. php:method:: read($length)

  :param $length: :doc:`int </api_ru/.types/int>` - count of bytes
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: readFully()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  :param $value: 
  :param $length: 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: seek($position)

  :param $position: 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: getPosition()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

