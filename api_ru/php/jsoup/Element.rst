Element
-----------------

.. include:: /api_ru.desc/php/jsoup/Element.header.rst

.. php:class:: php\\jsoup\\Element

 Class Element



**Methods**

----------

 .. php:method:: html($html)

  :param $html: :doc:`string </api_ru/.types/string>`  - (optional)
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: text()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: nodeName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: tagName($tagName)

  :param $tagName: :doc:`string </api_ru/.types/string>`  - (optional)
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: isBlock()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: id()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: attr($attributeKey, $attributeValue)

  :param $attributeKey: 
  :param $attributeValue: 
  :returns: :doc:`php\\jsoup\\$this </api_ru/php/jsoup/$this>` 

 .. php:method:: dataset()

  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:method:: parent()

  :returns: :doc:`php\\jsoup\\Element </api_ru/php/jsoup/Element>` 

 .. php:method:: parents()

  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: child($index)

  :param $index: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\jsoup\\Element </api_ru/php/jsoup/Element>` 

 .. php:method:: children()

  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 

 .. php:method:: select($cssQuery)

  :param $cssQuery: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_ru/php/jsoup/Elements>` 



.. include:: /api_ru.desc/php/jsoup/Element.footer.rst

