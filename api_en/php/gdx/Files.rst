Files
-------------

.. include:: /api_en.desc/php/gdx/Files.header.rst

.. php:class:: php\\gdx\\Files

 Class Files



**Methods**

----------

 .. php:method:: getFileHandle($path, $type)

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $type: :doc:`string </api_en/.types/string>`  - - Classpath, Internal, External, Absolute, Local
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: classpath($path)

  :param $path: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: internal($path)

  :param $path: 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: external($path)

  :param $path: 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: absolute($path)

  :param $path: 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: local($path)

  :param $path: 
  :returns: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 

 .. php:method:: getExternalStoragePath()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: isExternalStorageAvailable()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getLocalStoragePath()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: isLocalStorageAvailable()

  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/gdx/Files.footer.rst

