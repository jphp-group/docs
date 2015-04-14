XmlProcessor
--------------------

.. include:: /api_ru.desc/php/xml/XmlProcessor.header.rst

.. php:class:: php\\xml\\XmlProcessor

 **extends**: :doc:`php\\format\\Processor </api_ru/php/format/Processor>`




**Methods**

----------

 .. php:method:: format($value)

  :param $value: :doc:`php\\xml\\DomDocument </api_ru/php/xml/DomDocument>` 
  :returns: :doc:`string </api_ru/.types/string>` xml

 .. php:method:: formatTo($value, $output)

  :param $value: :doc:`php\\xml\\DomDocument </api_ru/php/xml/DomDocument>` 
  :param $output: :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 

 .. php:method:: parse($string)

  :param $string: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`, :doc:`string </api_ru/.types/string>`  - stream of string of xml
  :returns: :doc:`php\\xml\\DomDocument </api_ru/php/xml/DomDocument>` 

 .. php:method:: createDocument()

  :returns: :doc:`php\\xml\\DomDocument </api_ru/php/xml/DomDocument>` 



.. include:: /api_ru.desc/php/xml/XmlProcessor.footer.rst

