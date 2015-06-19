WebRequest
------------------------

.. include:: /api_en.desc/php/webserver/WebRequest.header.rst

.. php:class:: php\\webserver\\WebRequest

 Class WebRequest



**Properties**

----------

 .. php:attr:: method

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: scheme

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: pathInfo

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: servletPath

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: queryString

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: authType

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: url

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: port

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: ip

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: cookies

  :doc:`array </api_en/.types/array>`

  **read-only**


  Array of arrays [name, value, path, domain, httpOnly, secure, maxAge, comment]



**Methods**

----------

 .. php:method:: __construct($parent)

  **protected**


  :param $parent: :doc:`php\\webserver\\WebRequest </api_en/php/webserver/WebRequest>` 

 .. php:method:: getBody()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getBodyStream()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getMethod()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPathInfo()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getAuthType()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getQueryString()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getUrl()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getScheme()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPort()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getIp()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: current()

  :returns: :doc:`php\\webserver\\WebRequest </api_en/php/webserver/WebRequest>` 



.. include:: /api_en.desc/php/webserver/WebRequest.footer.rst

