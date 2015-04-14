URLConnection
---------------------

.. include:: /api_en.desc/php/net/URLConnection.header.rst

.. php:class:: php\\net\\URLConnection

 Class URLConnection



**Methods**

----------

 .. php:method:: connect()


 .. php:method:: setConnectTimeout($timeout)

  :param $timeout: :doc:`int </api_en/.types/int>`  - that specifies the connect timeout value in milliseconds

 .. php:method:: getConnectTimeout()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setReadTimeout($timeout)

  Sets the read timeout to a specified timeout, in
  milliseconds.

  :param $timeout: :doc:`int </api_en/.types/int>` 

 .. php:method:: getReadTimeout()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getURL()

  :returns: :doc:`php\\net\\URL </api_en/php/net/URL>` 

 .. php:method:: getContentLength()

  Returns the value of the ``content-length`` header field.

  :returns: :doc:`int </api_en/.types/int>` the content length of the resource that this connection's URL
  references, {@code -1} if the content length is not known,
  or if the content length is greater than Integer.MAX_VALUE.

 .. php:method:: getContentType()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getContentEncoding()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getExpiration()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDate()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getLastModified()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getHeaderField($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: getHeaderFields()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: getInputStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getOutputStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: toString()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setDoInput($doinput)

  :param $doinput: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDoInput()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setDoOutput($dooutput)

  :param $dooutput: 

 .. php:method:: getDoOutput()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setUseCaches($useCaches)

  :param $useCaches: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getUseCaches()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setIfModifiedSince($ifmodifiedsince)

  :param $ifmodifiedsince: :doc:`int </api_en/.types/int>` 

 .. php:method:: getIfModifiedSince()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setRequestProperty($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRequestProperty($name)

  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRequestProperties()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: disconnect()


 .. php:method:: getResponseCode()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getResponseMessage()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getInstanceFollowRedirects()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setInstanceFollowRedirects($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setChunkedStreamingMode($chunklen)

  This method is used to enable streaming of a HTTP request body
  without internal buffering, when the content length is <b>not</b>
  known in advance. In this mode, chunked transfer encoding
  is used to send the request body. Note, not all HTTP servers
  support this mode.

  :param $chunklen: :doc:`int </api_en/.types/int>`  - The number of bytes to write in each chunk.
  If chunklen is less than or equal to zero, a default
  value will be used.

 .. php:method:: setRequestMethod($method)

  Set the method for the URL request, one of:
  <UL>
  <LI>GET
  <LI>POST
  <LI>HEAD
  <LI>OPTIONS
  <LI>PUT
  <LI>DELETE
  <LI>TRACE
  </UL> are legal, subject to protocol restrictions.  The default
  method is GET.

  :param $method: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRequestMethod()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: usingProxy()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: guessContentTypeFromStream($stream)

  Tries to determine the type of an input stream based on the
  characters at the beginning of the input stream. This method can
  be used by subclasses that override the
  <code>getContentType</code> method.

  :param $stream: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: guessContentTypeFromName($name)

  :param $name: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/net/URLConnection.footer.rst

