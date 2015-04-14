DomElement
------------------

.. include:: /api_en.desc/php/xml/DomElement.header.rst

.. php:class:: php\\xml\\DomElement

 **abstract** class

 **extends**: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>`

**Children**

----------------------

 * **abstract** **class** :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>`



**Methods**

----------

 .. php:method:: __get($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` Value of attribute by $name

 .. php:method:: __set($name, $value)

  Set attribute value

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: __unset($name)

  Remove attribute by name

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: __isset($name)

  Check attribute exists by name

  :param $name: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getTagName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getAttribute($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: hasAttribute($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: hasAttributeNS($namespaceURI, $localName)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $localName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setAttribute($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: setAttributes($attributes)

  :param $attributes: :doc:`array </api_en/.types/array>`, :doc:`Traversable </api_en/Traversable>` 

 .. php:method:: removeAttribute($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: getElementsByTagName($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomNodeList </api_en/php/xml/DomNodeList>` 

 .. php:method:: getElementsByTagNameNS($namespaceURI, $localName)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $localName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomNodeList </api_en/php/xml/DomNodeList>` 

 .. php:method:: getAttributeNS($namespaceURI, $localName)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $localName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setAttributeNS($namespaceURI, $qualifiedName, $value)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $qualifiedName: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: removeAttributeNS($namespaceURI, $localName)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $localName: :doc:`string </api_en/.types/string>` 

 .. php:method:: setIdAttribute($name, $isId)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $isId: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setIdAttributeNS($namespaceURI, $localName, $isId)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $localName: :doc:`string </api_en/.types/string>` 
  :param $isId: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/xml/DomElement.footer.rst

