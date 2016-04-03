DomNode
---------------

.. include:: /api_en.desc/php/xml/DomNode.header.rst

.. php:class:: php\\xml\\DomNode

 **abstract** class

**Children**

----------------------

 * **abstract** **class** :doc:`php\\xml\\DomElement </api_en/php/xml/DomElement>`



**Methods**

----------

 .. php:method:: get($xpathExpression)

  :param $xpathExpression: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: find($xpathExpression)

  :param $xpathExpression: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: findAll($xpathExpression)

  :param $xpathExpression: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomNodeList </api_en/php/xml/DomNodeList>` 

 .. php:method:: getBaseURI()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getNamespaceURI()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getLocalName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getNodeType()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getNodeName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getNodeValue()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPrefix()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getTextContent()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getFirstChild()

  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: getLastChild()

  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: getNextSibling()

  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: getPreviousSibling()

  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: getParentNode()

  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: getOwnerDocument()

  :returns: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 

 .. php:method:: hasAttributes()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: hasChildNodes()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isDefaultNamespace($namespace)

  :param $namespace: :doc:`string </api_en/.types/string>` 

 .. php:method:: isEqualNode($node)

  :param $node: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isSameNode($node)

  :param $node: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isSupported($feature, $version)

  :param $feature: :doc:`string </api_en/.types/string>` 
  :param $version: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: lookupNamespaceURI($prefix)

  :param $prefix: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: lookupPrefix($namespaceURI)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: normalize()


 .. php:method:: setTextContent($content)

  :param $content: :doc:`string </api_en/.types/string>` 

 .. php:method:: setPrefix($prefix)

  :param $prefix: :doc:`string </api_en/.types/string>` 

 .. php:method:: cloneNode($deep)

  :param $deep: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: appendChild($node)

  :param $node: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`php\\xml\\$this </api_en/php/xml/$this>` 

 .. php:method:: removeChild($node)

  :param $node: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`php\\xml\\$this </api_en/php/xml/$this>` 

 .. php:method:: replaceChild($newNode, $oldNode)

  :param $newNode: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :param $oldNode: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`php\\xml\\$this </api_en/php/xml/$this>` 

 .. php:method:: insertBefore($newNode, $refNode)

  :param $newNode: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :param $refNode: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`php\\xml\\$this </api_en/php/xml/$this>` 

 .. php:method:: toModel()

  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/xml/DomNode.footer.rst

