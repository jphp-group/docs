ArchiveInputStream
-------------------------------

.. include:: /api_en.desc/php/compress/ArchiveInputStream.header.rst

.. php:class:: php\\compress\\ArchiveInputStream

 **extends**: :doc:`php\\io\\MiscStream </api_en/php/io/MiscStream>`


 jphp-compress-ext
 
 Class ArchiveInputStream for reading archive



**Methods**

----------

 .. php:method:: __construct($format, $source)

  :param $format: :doc:`string </api_en/.types/string>`  - zip, tar, jar
  :param $source: :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: nextEntry()

  :returns: :doc:`php\\compress\\ArchiveEntry </api_en/php/compress/ArchiveEntry>` 



.. include:: /api_en.desc/php/compress/ArchiveInputStream.footer.rst

