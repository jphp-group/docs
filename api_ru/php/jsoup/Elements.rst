Elements
------------------

.. include:: /api_ru.desc/php/jsoup/Elements.header.rst

.. php:class:: php\\jsoup\\Elements

 **implements**: :doc:`Traversable </api_ru/Traversable>`


 Class Elements



**Methods**

----------

 .. php:method:: text()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: hasText()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: html($html)

  :param $html: :doc:`string </api_ru/.types/string>`  - (optional)
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: outerHtml()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: attr($attributeKey)

  :param $attributeKey: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: hasAttr($attributeKey)

  :param $attributeKey: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: val($value)

  :param $value: :doc:`string </api_ru/.types/string>`  - (optional)
  :returns: :doc:`php\\jsoup\\$this </api_ru/php/jsoup/$this>` 

 .. php:method:: prepend($html)

  :param $html: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: append($html)

  :param $html: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: before($html)

  :param $html: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: after($html)

  :param $html: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: select($query)

  :param $query: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: not($query)

  :param $query: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: is($query)

  :param $query: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: parents()

  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 



.. include:: /api_ru.desc/php/jsoup/Elements.footer.rst

