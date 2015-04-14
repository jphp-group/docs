NetStream
-----------------

.. include:: /api_en.desc/php/net/NetStream.header.rst

.. php:class:: php\\net\\NetStream

 **extends**: :doc:`php\\io\\Stream </api_en/php/io/Stream>`


 http, ftp protocols
 
 Class NetStream



**Methods**

----------

 .. php:method:: read($length)

  :param $length: 

 .. php:method:: readFully($bufferSize = 4096)

  :param $bufferSize: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`mixed </api_en/.types/mixed>`, :doc:`void </api_en/.types/void>` 

 .. php:method:: readFullyWithCallback($bufferSize, $callback)

  :param $bufferSize: :doc:`int </api_en/.types/int>` 
  :param $callback: :doc:`callable </api_en/.types/callable>`  - (NetStream $this, $len)

 .. php:method:: write($value, $length = null)

  :param $value: 
  :param $length: 

 .. php:method:: eof()


 .. php:method:: seek($position)

  :param $position: 

 .. php:method:: getPosition()


 .. php:method:: close()


 .. php:method:: getUrl()

  :returns: :doc:`php\\net\\URL </api_en/php/net/URL>` 

 .. php:method:: setProxy($proxy)

  :param $proxy: :doc:`php\\net\\Proxy </api_en/php/net/Proxy>` 

 .. php:method:: getProxy()

  :returns: :doc:`php\\net\\Proxy </api_en/php/net/Proxy>` 

 .. php:method:: getUrlConnection()

  :returns: :doc:`php\\net\\URLConnection </api_en/php/net/URLConnection>` 



.. include:: /api_en.desc/php/net/NetStream.footer.rst

