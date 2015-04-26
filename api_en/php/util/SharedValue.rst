SharedValue
--------------------

.. include:: /api_en.desc/php/util/SharedValue.header.rst

.. php:class:: php\\util\\SharedValue

 **extends**: :doc:`php\\util\\SharedMemory </api_en/php/util/SharedMemory>`


 Class SharedValue



**Methods**

----------

 .. php:method:: __construct($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>`  - (optional)

 .. php:method:: get()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: set($value, $override = true)

  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :param $override: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: remove()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: isEmpty()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getAndSet($updateCallback)

  :param $updateCallback: :doc:`callable </api_en/.types/callable>`  - ($oldValue) returns a new value
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: setAndGet($updateCallback)

  :param $updateCallback: :doc:`callable </api_en/.types/callable>`  - ($oldValue) returns a new value
  :returns: :doc:`mixed </api_en/.types/mixed>` 



.. include:: /api_en.desc/php/util/SharedValue.footer.rst

