Connection
--------------------

.. include:: /api_ru.desc/php/jsoup/Connection.header.rst

.. php:class:: php\\jsoup\\Connection

 Class Connection



**Constants**

----------

 .. php:const:: METHOD_POST

 .. php:const:: METHOD_GET



**Methods**

----------

 .. php:method:: data($data)

  :param $data: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`php\\jsoup\\Connection </api_ru/php/jsoup/Connection>` 

 .. php:method:: cookies($data)

  :param $data: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`php\\jsoup\\Connection </api_ru/php/jsoup/Connection>` 

 .. php:method:: headers($data)

  :param $data: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`php\\jsoup\\Connection </api_ru/php/jsoup/Connection>` 

 .. php:method:: url($url)

  :param $url: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\jsoup\\Connection </api_ru/php/jsoup/Connection>` 

 .. php:method:: method($method)

  :param $method: :doc:`string </api_ru/.types/string>`  - POST or GET
  :returns: :doc:`php\\jsoup\\Connection </api_ru/php/jsoup/Connection>` 

 .. php:method:: execute()

  :returns: :doc:`php\\jsoup\\ConnectionResponse </api_ru/php/jsoup/ConnectionResponse>` 

 .. php:method:: get()

  

  :returns: :doc:`php\\jsoup\\Document </api_ru/php/jsoup/Document>` 

 .. php:method:: post()

  

  :returns: :doc:`php\\jsoup\\Document </api_ru/php/jsoup/Document>` 



.. include:: /api_ru.desc/php/jsoup/Connection.footer.rst

