ODatabase
----------------------

.. include:: /api_en.desc/php/orientdb/ODatabase.header.rst

.. php:class:: php\\orientdb\\ODatabase

 Class ODatabase



**Properties**

----------

 .. php:attr:: name

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: url

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: size

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: status

  :doc:`string </api_en/.types/string>`

  **read-only**


  OPEN, CLOSED, IMPORTING

 .. php:attr:: type

  :doc:`string </api_en/.types/string>`



**Methods**

----------

 .. php:method:: __construct($uri)

  :param $uri: :doc:`string </api_en/.types/string>` 

 .. php:method:: setUser($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: setUserAndPassword($name, $password)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $password: :doc:`string </api_en/.types/string>` 

 .. php:method:: exists()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: create()


 .. php:method:: drop()


 .. php:method:: open($username, $password)

  Open database

  :param $username: :doc:`string </api_en/.types/string>` 
  :param $password: :doc:`string </api_en/.types/string>` 

 .. php:method:: close()


 .. php:method:: reload()


 .. php:method:: freeze()


 .. php:method:: release()


 .. php:method:: begin()


 .. php:method:: commit($force = false)

  :param $force: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: rollback($force = false)

  :param $force: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDocuments($className)

  :param $className: 
  :returns: :doc:`php\\util\\Flow </api_en/php/util/Flow>` of ODocument

 .. php:method:: query($query, $limit = -1)

  :param $query: :doc:`string </api_en/.types/string>`  - like sql.
  :param $limit: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\util\\Flow </api_en/php/util/Flow>` of ODocument

 .. php:method:: command($query)

  :param $query: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`int </api_en/.types/int>` 



.. include:: /api_en.desc/php/orientdb/ODatabase.footer.rst

