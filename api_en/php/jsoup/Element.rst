Element
-----------------

.. include:: /api_en.desc/php/jsoup/Element.header.rst

.. php:class:: php\\jsoup\\Element

 **abstract** class




**Methods**

----------

 .. php:method:: html($html)

  :param $html: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: text()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: nodeName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: tagName($tagName)

  :param $tagName: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: isBlock()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: id()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: attr($attributeKey, $attributeValue)

  :param $attributeKey: 
  :param $attributeValue:  - (optional)
  :returns: :doc:`php\\jsoup\\$this </api_en/php/jsoup/$this>` 

 .. php:method:: dataset()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: parent()

  :returns: :doc:`php\\jsoup\\Element </api_en/php/jsoup/Element>` 

 .. php:method:: parents()

  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: child($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\jsoup\\Element </api_en/php/jsoup/Element>` 

 .. php:method:: children()

  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: select($cssQuery)

  :param $cssQuery: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 



.. include:: /api_en.desc/php/jsoup/Element.footer.rst

