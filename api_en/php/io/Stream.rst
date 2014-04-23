Stream
-------------

.. include:: /api_en.desc/php/io/Stream.header.rst

.. php:class:: php\\io\\Stream

 **abstract** class

 **implements**: :doc:`Iterator </api_en/Iterator>`




**Properties**

----------

 .. php:attr:: path

  :doc:`string </api_en/.types/string>`

  **private**


 .. php:attr:: mode

  :doc:`string </api_en/.types/string>`

  **private**




**Methods**

----------

 .. php:method:: read($length)

  **abstract**


  :param $length: :doc:`int </api_en/.types/int>` - count of bytes
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: readFully()

  **abstract**


  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  **abstract**


  :param $value: 
  :param $length: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: eof()

  **abstract**


  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: seek($position)

  **abstract**


  :param $position: 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getPosition()

  **abstract**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: close()

  **abstract**


  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: __construct($path, $mode = null)

  :param $path: 
  :param $mode: 
  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: setContext($context)

  :param $context: 
  :returns: :doc:`void </api_en/.types/void>` 

 .. php:method:: getContext()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: current()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: next()

  :returns: :doc:`void </api_en/.types/void>` 

 .. php:method:: key()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: rewind()

  :returns: :doc:`void </api_en/.types/void>` 

 .. php:staticmethod:: of($path, $mode = 'r')

  :param $path: 
  :param $mode: 
  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:staticmethod:: register($protocol, $className)

  :param $protocol: 
  :param $className: 

 .. php:staticmethod:: unregister($protocol)

  :param $protocol: 



.. include:: /api_en.desc/php/io/Stream.footer.rst

