Elements
------------------

.. include:: /api_en.desc/php/jsoup/Elements.header.rst

.. php:class:: php\\jsoup\\Elements

 **abstract** class

 **implements**: :doc:`Iterator </api_en/Iterator>`




**Methods**

----------

 .. php:method:: text()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: hasText()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: html($html)

  :param $html: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: outerHtml()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: attr($attributeKey, $value)

  :param $attributeKey: :doc:`string </api_en/.types/string>` 
  :param $value:  - (optional)
  :returns: :doc:`string </api_en/.types/string>`, :doc:`php\\jsoup\\$this </api_en/php/jsoup/$this>` 

 .. php:method:: hasAttr($attributeKey)

  :param $attributeKey: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: removeAttr($attributeKey)

  :param $attributeKey: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: addClass($class)

  :param $class: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: removeClass($class)

  :param $class: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: hasClass($class)

  :param $class: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: toggleClass($class)

  :param $class: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: val($value)

  :param $value: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`php\\jsoup\\$this </api_en/php/jsoup/$this>` 

 .. php:method:: prepend($html)

  :param $html: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: append($html)

  :param $html: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: before($html)

  :param $html: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: after($html)

  :param $html: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: select($query)

  :param $query: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: first()

  :returns: :doc:`php\\jsoup\\Element </api_en/php/jsoup/Element>` 

 .. php:method:: last()

  :returns: :doc:`php\\jsoup\\Element </api_en/php/jsoup/Element>` 

 .. php:method:: not($query)

  :param $query: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 

 .. php:method:: is($query)

  :param $query: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: parents()

  :returns: :doc:`php\\jsoup\\Elements </api_en/php/jsoup/Elements>` 



.. include:: /api_en.desc/php/jsoup/Elements.footer.rst

