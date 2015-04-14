Processor
--------------------

.. include:: /api_ru.desc/php/format/Processor.header.rst

.. php:class:: php\\format\\Processor

 **abstract** class

**Children**

----------------------

 * **class** :doc:`php\\format\\JsonProcessor </api_ru/php/format/JsonProcessor>`
 * **class** :doc:`php\\xml\\XmlProcessor </api_ru/php/xml/XmlProcessor>`



**Methods**

----------

 .. php:method:: format($value)

  **abstract**


  :param $value: 

 .. php:method:: formatTo($value, $output)

  **abstract**


  :param $value: 
  :param $output: :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 

 .. php:method:: parse($string)

  **abstract**


  :param $string: 



.. include:: /api_ru.desc/php/format/Processor.footer.rst

