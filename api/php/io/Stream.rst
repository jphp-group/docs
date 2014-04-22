Stream
-------------

.. php:class:: php\\io\\Stream

 **abstract** class

 **implements**: :doc:`Iterator </api/Iterator>`

 .. php:method:: read($length)

  **abstract**

  :param $length: :doc:`int </api/int>` - count of bytes
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: readFully()

  **abstract**

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: write($value, $length = null)

  **abstract**

  :param $value: 
  :param $length: 
  :returns: :doc:`int </api/int>` 

 .. php:method:: eof()

  **abstract**

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: seek($position)

  **abstract**

  :param $position: 
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: getPosition()

  **abstract**

  :returns: :doc:`int </api/int>` 

 .. php:method:: close()

  **abstract**

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: __construct($path, $mode = null)

  :param $path: 
  :param $mode: 
  :returns: :doc:`php\\io\\Stream </api/php/io/Stream>` 

 .. php:method:: setContext($context)

  :param $context: 
  :returns: :doc:`void </api/void>` 

 .. php:method:: getContext()

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: current()

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: next()

  :returns: :doc:`void </api/void>` 

 .. php:method:: key()

  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: rewind()

  :returns: :doc:`void </api/void>` 

 .. php:staticmethod:: of($path, $mode = 'r')

  :param $path: 
  :param $mode: 
  :returns: :doc:`php\\io\\Stream </api/php/io/Stream>` 

 .. php:staticmethod:: register($protocol, $className)

  :param $protocol: 
  :param $className: 

 .. php:staticmethod:: unregister($protocol)

  :param $protocol: 

