JsonProcessor
------------------------

.. include:: /api_en.desc/php/format/JsonProcessor.header.rst

.. php:class:: php\\format\\JsonProcessor

 **extends**: :doc:`php\\format\\Processor </api_en/php/format/Processor>`


 Class JsonProcessor



**Constants**

----------

 .. php:const:: SERIALIZE_PRETTY_PRINT

 .. php:const:: DESERIALIZE_AS_ARRAYS



**Methods**

----------

 .. php:method:: __construct($flags = 0)

  :param $flags: :doc:`int </api_en/.types/int>` 

 .. php:method:: parse($jsonString)

  :param $jsonString: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: format($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: onSerialize($nameOfType, $handler = null)

  :param $nameOfType: :doc:`string </api_en/.types/string>`  - - null, int, float, string, bool, object, array
  :param $handler: :doc:`callable </api_en/.types/callable>`  - (mixed $value) -> mixed

 .. php:method:: onClassSerialize($className, $handler = null)

  :param $className: :doc:`string </api_en/.types/string>` 
  :param $handler: :doc:`callable </api_en/.types/callable>` 



.. include:: /api_en.desc/php/format/JsonProcessor.footer.rst

