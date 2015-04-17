Jsoup
---------------

.. include:: /api_en.desc/php/jsoup/Jsoup.header.rst

.. php:class:: php\\jsoup\\Jsoup

 **final** class




**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: connect($url)

  :param $url: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Connection </api_en/php/jsoup/Connection>` 

 .. php:staticmethod:: parse($source, $encoding, $baseUri)

  :param $source: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $encoding: :doc:`string </api_en/.types/string>` 
  :param $baseUri: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\jsoup\\Document </api_en/php/jsoup/Document>` 

 .. php:staticmethod:: parseText($text, $baseUri)

  :param $text: :doc:`string </api_en/.types/string>` 
  :param $baseUri: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`php\\jsoup\\Document </api_en/php/jsoup/Document>` 



.. include:: /api_en.desc/php/jsoup/Jsoup.footer.rst

