DomDocument
-------------------

.. include:: /api_en.desc/php/xml/DomDocument.header.rst

.. php:class:: php\\xml\\DomDocument

 **abstract** class

 **extends**: :doc:`php\\xml\\DomElement </api_en/php/xml/DomElement>`




**Methods**

----------

 .. php:method:: getDocumentElement()

  :returns: :doc:`php\\xml\\DomDocument </api_en/php/xml/DomDocument>` 

 .. php:method:: getElementById($id)

  :param $id: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomElement </api_en/php/xml/DomElement>` 

 .. php:method:: getInputEncoding()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getXmlEncoding()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getXmlVersion()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getXmlStandalone()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setXmlStandalone($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getStrictErrorChecking()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setStrictErrorChecking($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDocumentURI()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setDocumentURI($value)

  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: createElement($tagName, $model)

  :param $tagName: :doc:`string </api_en/.types/string>` 
  :param $model: :doc:`Traversable </api_en/Traversable>`, :doc:`array </api_en/.types/array>`  - (optional)
  :returns: :doc:`php\\xml\\DomElement </api_en/php/xml/DomElement>` 

 .. php:method:: createElementNS($namespaceURI, $qualifiedName)

  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $qualifiedName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomElement </api_en/php/xml/DomElement>` 

 .. php:method:: createProcessingInstruction($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: importNode($importedNode, $deep)

  :param $importedNode: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :param $deep: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: adoptNode($source)

  :param $source: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :returns: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 

 .. php:method:: renameNode($node, $namespaceURI, $qualifiedName)

  :param $node: :doc:`php\\xml\\DomNode </api_en/php/xml/DomNode>` 
  :param $namespaceURI: :doc:`string </api_en/.types/string>` 
  :param $qualifiedName: :doc:`string </api_en/.types/string>` 

 .. php:method:: normalizeDocument()




.. include:: /api_en.desc/php/xml/DomDocument.footer.rst

