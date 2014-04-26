FileStream
-----------------

.. include:: /api_ru.desc/php/io/FileStream.header.rst

.. php:class:: php\\io\\FileStream

 **extends**: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`




**Methods**

----------

 .. php:method:: read($length)

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $length: :doc:`int </api_ru/.types/int>`  - - count of bytes
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: readFully()

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $value: :doc:`string </api_ru/.types/string>` 
  :param $length: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: seek($position)

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $position: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: getPosition()

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: length()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getFilePointer()

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: truncate($size)

  **throws** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`

  :param $size: :doc:`int </api_ru/.types/int>` 



.. include:: /api_ru.desc/php/io/FileStream.footer.rst

