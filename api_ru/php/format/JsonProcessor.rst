JsonProcessor
------------------------

.. include:: /api_ru.desc/php/format/JsonProcessor.header.rst

.. php:class:: php\\format\\JsonProcessor

 **extends**: :doc:`php\\format\\Processor </api_ru/php/format/Processor>`


 Class JsonProcessor



**Constants**

----------

 .. php:const:: SERIALIZE_PRETTY_PRINT

 .. php:const:: DESERIALIZE_AS_ARRAYS



**Methods**

----------

 .. php:method:: __construct($flags = 0)

  :param $flags: :doc:`int </api_ru/.types/int>` 

 .. php:method:: parse($jsonString)

  :param $jsonString: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: format($value)

  :param $value: :doc:`mixed </api_ru/.types/mixed>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: onSerialize($nameOfType, $handler = null)

  :param $nameOfType: :doc:`string </api_ru/.types/string>`  - - null, int, float, string, bool, object, array
  :param $handler: :doc:`callable </api_ru/.types/callable>`  - (mixed $value) -> mixed

 .. php:method:: onClassSerialize($className, $handler = null)

  :param $className: :doc:`string </api_ru/.types/string>` 
  :param $handler: :doc:`callable </api_ru/.types/callable>` 



.. include:: /api_ru.desc/php/format/JsonProcessor.footer.rst

