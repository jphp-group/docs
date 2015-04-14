AssetManager
---------------------------

.. include:: /api_ru.desc/php/gdx/assets/AssetManager.header.rst

.. php:class:: php\\gdx\\assets\\AssetManager



**Methods**

----------

 .. php:method:: __construct($resolver)

  :param $resolver: :doc:`callable </api_ru/.types/callable>`  - (optional) - function($fileName): FileHandle

 .. php:method:: get($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\gdx\\graphics\\Texture </api_ru/php/gdx/graphics/Texture>`, :doc:`php\\gdx\\graphics\\Pixmap </api_ru/php/gdx/graphics/Pixmap>`, :doc:`php\\gdx\\audio\\Music </api_ru/php/gdx/audio/Music>`, :doc:`php\\gdx\\audio\\Sound </api_ru/php/gdx/audio/Sound>` 

 .. php:method:: loadTexture($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: loadPixmap($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: loadMusic($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: loadSound($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: unload($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: isLoaded($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: containsAsset($asset)

  :param $asset: :doc:`object </api_ru/.types/object>`, :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: getAssetFileName($asset)

  :param $asset: :doc:`object </api_ru/.types/object>`, :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: disposeDependencies($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: update($millis)

  :param $millis: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: finishLoading()


 .. php:method:: getLoadedAssets()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getQueuedAssets()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getProgress()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: dispose()


 .. php:method:: clear()


 .. php:method:: getReferenceCount($fileName)

  :param $fileName: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: setReferenceCount($fileName, $refCount)

  :param $fileName: :doc:`string </api_ru/.types/string>` 
  :param $refCount: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getDiagnostics()

  :returns: :doc:`string </api_ru/.types/string>` 



.. include:: /api_ru.desc/php/gdx/assets/AssetManager.footer.rst

