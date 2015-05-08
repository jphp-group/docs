WebResponse
-------------------------

.. include:: /api_en.desc/php/webserver/WebResponse.header.rst

.. php:class:: php\\webserver\\WebResponse

 Class WebResponse



**Properties**

----------

 .. php:attr:: status

  :doc:`int </api_en/.types/int>`

 .. php:attr:: contentType

  :doc:`string </api_en/.types/string>`

 .. php:attr:: characterEncoding

  :doc:`string </api_en/.types/string>`

 .. php:attr:: bufferSize

  :doc:`int </api_en/.types/int>`



**Methods**

----------

 .. php:method:: __construct($parent)

  **protected**


  :param $parent: :doc:`php\\webserver\\WebResponse </api_en/php/webserver/WebResponse>` 

 .. php:method:: setHeader($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getHeader($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getHeaders($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string[] </api_en/.types/string>` 

 .. php:method:: getHeaderNames()

  :returns: :doc:`string[] </api_en/.types/string>` 

 .. php:method:: addHeader($name, $value)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: redirect($location, $httpStatus = 301)

  :param $location: :doc:`string </api_en/.types/string>` 
  :param $httpStatus: :doc:`int </api_en/.types/int>` 

 .. php:method:: encodeRedirectURL($url)

  :param $url: :doc:`string </api_en/.types/string>` 

 .. php:method:: writeToBody($content)

  :param $content: :doc:`string </api_en/.types/string>` 

 .. php:method:: setContentLength($length)

  :param $length: :doc:`int </api_en/.types/int>` 

 .. php:method:: addCookie($cookie)

  :param $cookie: :doc:`array </api_en/.types/array>`  - [name, value, maxAge, path, domain, httpOnly, secure, comment]

 .. php:method:: getStatus()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setStatus($status)

  **protected**


  :param $status: :doc:`int </api_en/.types/int>` 

 .. php:method:: getContentType()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setContentType($contentType)

  **protected**


  :param $contentType: :doc:`string </api_en/.types/string>` 

 .. php:method:: getCharacterEncoding()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setCharacterEncoding($characterEncoding)

  **protected**


  :param $characterEncoding: :doc:`string </api_en/.types/string>` 

 .. php:method:: getBufferSize()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setBufferSize($bufferSize)

  **protected**


  :param $bufferSize: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: current()

  :returns: :doc:`php\\webserver\\WebResponse </api_en/php/webserver/WebResponse>` 



.. include:: /api_en.desc/php/webserver/WebResponse.footer.rst

