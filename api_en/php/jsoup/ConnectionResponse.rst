ConnectionResponse
----------------------------

.. include:: /api_en.desc/php/jsoup/ConnectionResponse.header.rst

.. php:class:: php\\jsoup\\ConnectionResponse

 **abstract** class




**Methods**

----------

 .. php:method:: statusCode()

  Get the status code of the response.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: statusMessage()

  Get the status message of the response.

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: charset()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: body()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: bodyAsBytes()

  :returns: :doc:`string </api_en/.types/string>` binary string

 .. php:method:: contentType()

  Get the response content type (e.g. "text/html");

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: parse()

  :returns: :doc:`php\\jsoup\\Document </api_en/php/jsoup/Document>` 



.. include:: /api_en.desc/php/jsoup/ConnectionResponse.footer.rst

