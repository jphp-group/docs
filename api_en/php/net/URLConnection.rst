URLConnection
---------------------

.. include:: /api_en.desc/php/net/URLConnection.header.rst

.. php:class:: php\\net\\URLConnection

 Class URLConnection



**Properties**

----------

 .. php:attr:: doOutput

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: doInput

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: requestMethod

  :doc:`string </api_en/.types/string>`

  POST, GET, PUT, etc.

 .. php:attr:: connectTimeout

  :doc:`php\\net\\int millis </api_en/php/net/int millis>`

  that specifies the connect timeout value in milliseconds

 .. php:attr:: readTimeout

  :doc:`php\\net\\int millis </api_en/php/net/int millis>`

  the read timeout to a specified timeout, in milliseconds.

 .. php:attr:: useCaches

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: ifModifiedSince

  :doc:`php\\net\\int millis </api_en/php/net/int millis>`

 .. php:attr:: followRedirects

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: url

  :doc:`php\\net\\URL </api_en/php/net/URL>`

  **read-only**


 .. php:attr:: responseCode

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: responseMessage

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: contentLength

  :doc:`php\\net\\int bytes </api_en/php/net/int bytes>`

  **read-only**


  int the content length of the resource that this connection's URL
  references, -1 if the content length is not known,
  or if the content length is greater than Integer.MAX_VALUE.

 .. php:attr:: contentType

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: contentEncoding

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: expiration

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: lastModified

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: usingProxy

  :doc:`bool </api_en/.types/bool>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($parent)

  **protected**


  :param $parent: :doc:`php\\net\\URLConnection </api_en/php/net/URLConnection>` 

 .. php:method:: connect()


 .. php:method:: getHeaderField($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: getHeaderFields()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: getInputStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getErrorStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getOutputStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: setRequestProperty($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRequestProperty($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRequestProperties()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: disconnect()


 .. php:method:: setChunkedStreamingMode($chunklen)

  This method is used to enable streaming of a HTTP request body
  without internal buffering, when the content length is <b>not</b>
  known in advance. In this mode, chunked transfer encoding
  is used to send the request body. Note, not all HTTP servers
  support this mode.

  :param $chunklen: :doc:`int </api_en/.types/int>`  - The number of bytes to write in each chunk.
  If chunklen is less than or equal to zero, a default
  value will be used.

 .. php:staticmethod:: guessContentTypeFromStream($stream)

  Tries to determine the type of an input stream based on the
  characters at the beginning of the input stream. This method can
  be used by subclasses that override the
  <code>getContentType</code> method.

  :param $stream: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: guessContentTypeFromName($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: create($url, $proxy = null)

  :param $url: :doc:`string </api_en/.types/string>` 
  :param $proxy: :doc:`php\\net\\Proxy </api_en/php/net/Proxy>` 
  :returns: :doc:`php\\net\\URLConnection </api_en/php/net/URLConnection>` 



.. include:: /api_en.desc/php/net/URLConnection.footer.rst

