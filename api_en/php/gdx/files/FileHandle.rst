FileHandle
------------------------

.. include:: /api_en.desc/php/gdx/files/FileHandle.header.rst

.. php:class:: php\\gdx\\files\\FileHandle

 Class FileHandle



**Methods**

----------

 .. php:method:: __construct($path)

  :param $path: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: path()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: name()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: extension()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: nameWithoutExtension()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: pathWithoutExtension()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: type()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: file()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: read()

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: readString($charset)

  :param $charset: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: readBytes()

  :returns: :doc:`string </api_en/.types/string>` binary

 .. php:method:: write($append, $bufferSize)

  :param $append: :doc:`bool </api_en/.types/bool>` 
  :param $bufferSize: :doc:`int </api_en/.types/int>`  - (optional)
  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: writeString($string, $append, $charset)

  :param $string: :doc:`string </api_en/.types/string>` 
  :param $append: :doc:`bool </api_en/.types/bool>` 
  :param $charset: :doc:`string </api_en/.types/string>`  - (optional)

 .. php:method:: writeBytes($binaryString, $append)

  :param $binaryString: :doc:`string </api_en/.types/string>` 
  :param $append: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getList($suffix)

  :param $suffix: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`php\\gdx\\files\\FileHandle[] </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: isDirectory()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: child($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: sibling($name)

  :param $name: 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: parent()

  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: mkdirs()

  **throws** :doc:`php\\gdx\\files\\\\Exception </api_en/php/gdx/files//Exception>`


 .. php:method:: exists()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: delete()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: deleteDirectory()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: emptyDirectory($preserveTree)

  :param $preserveTree: :doc:`bool </api_en/.types/bool>`  - (optional)

 .. php:method:: copyTo($fileHandle)

  :param $fileHandle: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: moveTo($fileHandle)

  :param $fileHandle: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: length()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: lastModified()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: tempFile($suffix)

  :param $suffix: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:staticmethod:: tempDirectory($suffix)

  :param $suffix: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 



.. include:: /api_en.desc/php/gdx/files/FileHandle.footer.rst

