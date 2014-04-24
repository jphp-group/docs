FileStream
-----------------

.. include:: /api_ru.desc/php/io/FileStream.header.rst

.. php:class:: php\\io\\FileStream

 **extends**: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`




**Methods**

----------

 .. php:method:: read($length)

  :param $length: :doc:`int </api_ru/.types/int>`  - - count of bytes
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: readFully()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  :param $value: :doc:`string </api_ru/.types/string>` 
  :param $length: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: seek($position)

  :param $position: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: getPosition()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: length()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getFilePointer()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: truncate($size)

  :param $size: :doc:`int </api_ru/.types/int>` 



.. include:: /api_ru.desc/php/io/FileStream.footer.rst

