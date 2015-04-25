WebServer
-----------------------

.. include:: /api_en.desc/php/webserver/WebServer.header.rst

.. php:class:: php\\webserver\\WebServer

 Embedded http web server.
 
 Class WebServer



**Methods**

----------

 .. php:method:: __construct($onRequest = null)

  :param $onRequest: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: run()


 .. php:method:: setRoute($onRequest)

  :param $onRequest: :doc:`callable </api_en/.types/callable>`  - (WebRequest $request, WebResponse $response)

 .. php:method:: setHotReload($enabled)

  :param $enabled: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setIsolated($enabled)

  :param $enabled: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: addStaticHandler($handler)

  :param $handler: :doc:`array </api_en/.types/array>`  - [path, location, cache, cachePeriod, gzip]

 .. php:method:: setPort($port)

  :param $port: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\webserver\\WebServer </api_en/php/webserver/WebServer>` 



.. include:: /api_en.desc/php/webserver/WebServer.footer.rst

