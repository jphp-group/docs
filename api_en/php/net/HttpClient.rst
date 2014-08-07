HttpClient
------------------

.. include:: /api_en.desc/php/net/HttpClient.header.rst

.. php:class:: php\\net\\HttpClient

 Class HttpClient
 
 Cloneable



**Methods**

----------

 .. php:method:: getHeaders()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: setHeaders($headers)

  :param $headers: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: setConnectTimeout($value)

  :param $value: :doc:`int </api_en/.types/int>`  - - in milliseconds
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: setSocketTimeout($value)

  :param $value: :doc:`int </api_en/.types/int>`  - - in milliseconds
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: setMaxRedirects($value)

  :param $value: :doc:`int </api_en/.types/int>`  - -1 means that no limits
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: setRedirectsEnabled($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: setProxy($hostname, $port = -1, $scheme = 'http')

  :param $hostname: :doc:`string </api_en/.types/string>` 
  :param $port: :doc:`int </api_en/.types/int>` 
  :param $scheme: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\net\\HttpClient </api_en/php/net/HttpClient>` 

 .. php:method:: get($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: post($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: put($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: delete($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: head($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: patch($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 

 .. php:method:: options($url)

  :param $url: 
  :returns: :doc:`php\\net\\HttpRequest </api_en/php/net/HttpRequest>` 



.. include:: /api_en.desc/php/net/HttpClient.footer.rst

