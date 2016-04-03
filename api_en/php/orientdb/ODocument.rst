ODocument
----------------------

.. include:: /api_en.desc/php/orientdb/ODocument.header.rst

.. php:class:: php\\orientdb\\ODocument

 Class ODocument



**Properties**

----------

 .. php:attr:: id

  :doc:`string </api_en/.types/string>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($className)

  :param $className: :doc:`string </api_en/.types/string>` 

 .. php:method:: isNew()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: resetId()


 .. php:method:: save()


 .. php:method:: delete()


 .. php:method:: clear()


 .. php:method:: reset()


 .. php:method:: undo($field)

  Undo changes.

  :param $field:  - (optional)

 .. php:method:: load()


 .. php:method:: reload()


 .. php:method:: toJson()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: fromJson($json)

  :param $json: :doc:`string </api_en/.types/string>` 

 .. php:method:: __set($name, $value)

  :param $name: 
  :param $value: 

 .. php:method:: __get($name)

  :param $name: 

 .. php:method:: __isset($name)

  :param $name: 

 .. php:method:: __unset($name)

  :param $name: 

 .. php:method:: __clone()




.. include:: /api_en.desc/php/orientdb/ODocument.footer.rst

