SharedMap
------------------

.. include:: /api_en.desc/php/util/SharedMap.header.rst

.. php:class:: php\\util\\SharedMap

 **extends**: :doc:`php\\util\\SharedCollection </api_en/php/util/SharedCollection>`


 Class SharedMap



**Methods**

----------

 .. php:method:: __construct($array)

  :param $array: :doc:`array </api_en/.types/array>`, :doc:`Traversable </api_en/Traversable>`  - (optional)

 .. php:method:: get($key, $default = null)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $default: :doc:`mixed </api_en/.types/mixed>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getOrCreate($key, $createCallback)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $createCallback: :doc:`callable </api_en/.types/callable>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: has($key)

  :param $key: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: count()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: set($key, $value, $override = true)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :param $override: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` previous value

 .. php:method:: remove($key)

  :param $key: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: clear()


 .. php:method:: isEmpty()

  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/util/SharedMap.footer.rst

