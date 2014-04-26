Stream
-------------

.. include:: /api_ru.desc/php/io/Stream.header.rst

.. php:class:: php\\io\\Stream

 **abstract** class

**Children**

----------------------

 * **class** :doc:`php\\io\\FileStream </api_ru/php/io/FileStream>`
 * **class** :doc:`php\\io\\MiscStream </api_ru/php/io/MiscStream>`
 * **class** :doc:`php\\io\\ResourceStream </api_ru/php/io/ResourceStream>`



**Properties**

----------

 .. php:attr:: path

  :doc:`string </api_ru/.types/string>`

  **private**


 .. php:attr:: mode

  :doc:`string </api_ru/.types/string>`

  **private**




**Methods**

----------

 .. php:method:: read($length)

  **abstract**


  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $length: :doc:`int </api_ru/.types/int>`  - - count of bytes
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: readFully()

  **abstract**


  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  **abstract**


  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $value: :doc:`string </api_ru/.types/string>` 
  :param $length: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: eof()

  **abstract**


  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: seek($position)

  **abstract**


  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $position: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: getPosition()

  **abstract**


  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: close()

  **abstract**


  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: __construct($path, $mode = null)

  :param $path: :doc:`string </api_ru/.types/string>` 
  :param $mode: :doc:`null </api_ru/.types/null>`, :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 

 .. php:method:: setContext($context)

  :param $context: 
  :returns: :doc:`void </api_ru/.types/void>` 

 .. php:method:: getContext()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:staticmethod:: of($path, $mode = 'r')

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $path: :doc:`string </api_ru/.types/string>` 
  :param $mode: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 

 .. php:staticmethod:: register($protocol, $className)

  :param $protocol: :doc:`string </api_ru/.types/string>` 
  :param $className: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: unregister($protocol)

  :param $protocol: 



.. include:: /api_ru.desc/php/io/Stream.footer.rst

