Processor
--------------------

.. include:: /api_en.desc/php/format/Processor.header.rst

.. php:class:: php\\format\\Processor

 **abstract** class

**Children**

----------------------

 * **class** :doc:`php\\format\\JsonProcessor </api_en/php/format/JsonProcessor>`
 * **class** :doc:`php\\xml\\XmlProcessor </api_en/php/xml/XmlProcessor>`



**Methods**

----------

 .. php:method:: format($value)

  **abstract**


  :param $value: 

 .. php:method:: formatTo($value, $output)

  **abstract**


  :param $value: 
  :param $output: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: parse($string)

  **abstract**


  :param $string: 



.. include:: /api_en.desc/php/format/Processor.footer.rst

