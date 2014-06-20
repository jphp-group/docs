HttpEntity
------------------

.. include:: /api_ru.desc/php/net/HttpEntity.header.rst

.. php:class:: php\\net\\HttpEntity

 Class HttpEntity



**Methods**

----------

 .. php:method:: __construct($source)

  :param $source: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`, :doc:`string </api_ru/.types/string>` 

 .. php:method:: getContent()

  :returns: :doc:`php\\io\\Stream </api_ru/php/io/Stream>` 

 .. php:method:: getContentType()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getContentEncoding()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getContentLength()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isChunked()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isRepeatable()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isStreaming()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: toString($encoding = null)

  :param $encoding: :doc:`null </api_ru/.types/null>`, :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 



.. include:: /api_ru.desc/php/net/HttpEntity.footer.rst

