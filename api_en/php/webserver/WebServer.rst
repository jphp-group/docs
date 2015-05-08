WebServer
-----------------------

.. include:: /api_en.desc/php/webserver/WebServer.header.rst

.. php:class:: php\\webserver\\WebServer

 Embedded http web server.
 
 Class WebServer



**Properties**

----------

 .. php:attr:: id

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: port

  :doc:`int </api_en/.types/int>`

 .. php:attr:: isolated

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: importAutoloaders

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: hotReload

  :doc:`bool </api_en/.types/bool>`



**Methods**

----------

 .. php:method:: __construct($onRequest)

  :param $onRequest: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: run()


 .. php:method:: addStaticHandler($handler)

  :param $handler: :doc:`array </api_en/.types/array>`  - [path, location, cache, cachePeriod, gzip]
  :returns: :doc:`php\\webserver\\WebServer </api_en/php/webserver/WebServer>` 

 .. php:method:: getId()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPort()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setPort($port)

  **protected**


  :param $port: :doc:`int </api_en/.types/int>` 

 .. php:method:: isIsolated()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setIsolated($isolated)

  **protected**


  :param $isolated: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: isImportAutoloaders()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setImportAutoloaders($importAutoloaders)

  **protected**


  :param $importAutoloaders: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: isHotReload()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setHotReload($hotReload)

  **protected**


  :param $hotReload: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: __clone()

  **private**



 .. php:staticmethod:: current()

  :returns: :doc:`php\\webserver\\WebServer </api_en/php/webserver/WebServer>` 



.. include:: /api_en.desc/php/webserver/WebServer.footer.rst

