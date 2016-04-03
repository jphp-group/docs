ArchiveOutputStream
--------------------------------

.. include:: /api_en.desc/php/compress/ArchiveOutputStream.header.rst

.. php:class:: php\\compress\\ArchiveOutputStream

 **extends**: :doc:`php\\io\\MiscStream </api_en/php/io/MiscStream>`


 jphp-compress-ext
 
 Class ArchiveOutputStream for creating archives



**Methods**

----------

 .. php:method:: __construct($format, $source)

  :param $format: :doc:`string </api_en/.types/string>`  - zip, tar, jar, ar
  :param $source: :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: createEntry($file, $name)

  :param $file: :doc:`string </api_en/.types/string>` 
  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\compress\\ArchiveEntry </api_en/php/compress/ArchiveEntry>` 

 .. php:method:: addFile($file, $name)

  :param $file: :doc:`string </api_en/.types/string>` 
  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\compress\\ArchiveEntry </api_en/php/compress/ArchiveEntry>` 

 .. php:method:: addEntry($entry)

  :param $entry: :doc:`php\\compress\\ArchiveEntry </api_en/php/compress/ArchiveEntry>` 

 .. php:method:: canAddEntry($entry)

  :param $entry: :doc:`php\\compress\\ArchiveEntry </api_en/php/compress/ArchiveEntry>` 

 .. php:method:: closeEntry()




.. include:: /api_en.desc/php/compress/ArchiveOutputStream.footer.rst

