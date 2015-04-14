AssetManager
---------------------------

.. include:: /api_en.desc/php/gdx/assets/AssetManager.header.rst

.. php:class:: php\\gdx\\assets\\AssetManager



**Methods**

----------

 .. php:method:: __construct($resolver)

  :param $resolver: :doc:`callable </api_en/.types/callable>`  - (optional) - function($fileName): FileHandle

 .. php:method:: get($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\gdx\\graphics\\Texture </api_en/php/gdx/graphics/Texture>`, :doc:`php\\gdx\\graphics\\Pixmap </api_en/php/gdx/graphics/Pixmap>`, :doc:`php\\gdx\\audio\\Music </api_en/php/gdx/audio/Music>`, :doc:`php\\gdx\\audio\\Sound </api_en/php/gdx/audio/Sound>` 

 .. php:method:: loadTexture($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: loadPixmap($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: loadMusic($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: loadSound($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: unload($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: isLoaded($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: containsAsset($asset)

  :param $asset: :doc:`object </api_en/.types/object>`, :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getAssetFileName($asset)

  :param $asset: :doc:`object </api_en/.types/object>`, :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: disposeDependencies($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 

 .. php:method:: update($millis)

  :param $millis: :doc:`int </api_en/.types/int>`  - (optional)

 .. php:method:: finishLoading()


 .. php:method:: getLoadedAssets()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getQueuedAssets()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getProgress()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: dispose()


 .. php:method:: clear()


 .. php:method:: getReferenceCount($fileName)

  :param $fileName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setReferenceCount($fileName, $refCount)

  :param $fileName: :doc:`string </api_en/.types/string>` 
  :param $refCount: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDiagnostics()

  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/gdx/assets/AssetManager.footer.rst

