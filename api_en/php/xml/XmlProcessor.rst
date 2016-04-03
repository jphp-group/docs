XmlProcessor
--------------------

.. include:: /api_en.desc/php/xml/XmlProcessor.header.rst

.. php:class:: php\\xml\\XmlProcessor

 **extends**: :doc:`php\\format\\Processor </api_en/php/format/Processor>`


 Class XmlProcessor



**Methods**

----------

 .. php:method:: format($value)

  **throws** :doc:`php\\format\\ProcessorException </api_en/php/format/ProcessorException>`

  :param $value: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 
  :returns: :doc:`string </api_en/.types/string>` xml

 .. php:method:: formatTo($value, $output)

  **throws** :doc:`php\\format\\ProcessorException </api_en/php/format/ProcessorException>`

  :param $value: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 
  :param $output: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: parse($string)

  **throws** :doc:`php\\format\\ProcessorException </api_en/php/format/ProcessorException>`

  :param $string: :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`string </api_en/.types/string>`  - stream of string of xml
  :returns: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 

 .. php:method:: createDocument()

  :returns: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 



.. include:: /api_en.desc/php/xml/XmlProcessor.footer.rst

