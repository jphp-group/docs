ResourceStream
---------------------

.. include:: /api_ru.desc/php/io/ResourceStream.header.rst

.. php:class:: php\\io\\ResourceStream

 **extends**: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`


 Class ResourceStream



**Methods**

----------

 .. php:method:: __construct($path)

  :param $path: :doc:`string </api_ru/.types/string>` 

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

 .. php:staticmethod:: getResources($name)

  :param $name: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\io\\ResourceStream[] </api_ru/php/io/ResourceStream>` 



.. include:: /api_ru.desc/php/io/ResourceStream.footer.rst

