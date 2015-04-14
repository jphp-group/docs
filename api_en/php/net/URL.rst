URL
-----------

.. include:: /api_en.desc/php/net/URL.header.rst

.. php:class:: php\\net\\URL

 Class URL



**Methods**

----------

 .. php:method:: __construct($uri)

  :param $uri: :doc:`string </api_en/.types/string>` 

 .. php:method:: openConnection($proxy)

  :param $proxy: :doc:`php\\net\\Proxy </api_en/php/net/Proxy>`  - (optional)
  :returns: :doc:`php\\net\\URLConnection </api_en/php/net/URLConnection>` 

 .. php:method:: getAuthority()

  Gets the authority part of this ``URL``

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPort()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDefaultPort()

  Gets the default port number of the protocol associated
  with this ``URL``. If the URL scheme or the URLStreamHandler
  for the URL do not define a default port number,
  then -1 is returned.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getProtocol()

  Gets the protocol name of this ``URL``

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getHost()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getFile()

  Gets the file name of this <code>URL</code>.
  The returned file portion will be
  the same as ``getPath()``, plus the concatenation of
  the value of ``getQuery()``, if any. If there is
  no query portion, this method and ``getPath()`` will
  return identical results.

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPath()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getQuery()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRef()

  Gets the anchor (also known as the "reference") of this URL

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: sameFile($url)

  Compares two URLs, excluding the fragment component.

  :param $url: :doc:`php\\net\\URL </api_en/php/net/URL>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: toString()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: toExternalForm()

  Constructs a string representation of this URL. The
  string is created by calling the toExternalForm
  method of the stream protocol handler for this object.

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: openStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: __toString()

  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/net/URL.footer.rst

