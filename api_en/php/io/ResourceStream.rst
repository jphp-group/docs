ResourceStream
---------------------

.. include:: /api_en.desc/php/io/ResourceStream.header.rst

.. php:class:: php\\io\\ResourceStream

 **extends**: :doc:`php\\io\\Stream </api_en/php/io/Stream>`


 Class ResourceStream



**Methods**

----------

 .. php:method:: __construct($path)

  :param $path: :doc:`string </api_en/.types/string>` 

 .. php:method:: read($length)

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :param $length: :doc:`int </api_en/.types/int>`  - - count of bytes
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: readFully()

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: write($value, $length = null)

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :param $value: :doc:`string </api_en/.types/string>` 
  :param $length: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: eof()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: seek($position)

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :param $position: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getPosition()

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: close()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: getResources($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\io\\ResourceStream[] </api_en/php/io/ResourceStream>` 



.. include:: /api_en.desc/php/io/ResourceStream.footer.rst

