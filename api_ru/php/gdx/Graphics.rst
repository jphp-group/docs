Graphics
----------------

.. include:: /api_ru.desc/php/gdx/Graphics.header.rst

.. php:class:: php\\gdx\\Graphics

 Class Graphics



**Methods**

----------

 .. php:method:: isGL30Available()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getWidth()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getHeight()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getDeltaTime()

  :returns: :doc:`double </api_ru/.types/double>` 

 .. php:method:: getRawDeltaTime()

  :returns: :doc:`double </api_ru/.types/double>` 

 .. php:method:: getFramesPerSecond()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getDensity()

  :returns: :doc:`float </api_ru/.types/float>` 

 .. php:method:: supportsDisplayModeChange()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getDisplayModes()

  :returns: :doc:`php\\gdx\\DisplayMode[] </api_ru/php/gdx/DisplayMode>` the supported fullscreen DisplayMode(s)

 .. php:method:: getDesktopDisplayMode()

  :returns: :doc:`php\\gdx\\graphics\\DisplayMode </api_ru/php/gdx/graphics/DisplayMode>` 

 .. php:method:: setDisplayMode($widthOrDisplayMode, $height, $fullscreen)

  :param $widthOrDisplayMode: :doc:`php\\gdx\\graphics\\DisplayMode </api_ru/php/gdx/graphics/DisplayMode>`, :doc:`int </api_ru/.types/int>` 
  :param $height: :doc:`int </api_ru/.types/int>`  - (optional)
  :param $fullscreen: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: setTitle($title)

  :param $title: :doc:`string </api_ru/.types/string>` 

 .. php:method:: setVSync($vsync)

  :param $vsync: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: supportsExtension($extension)

  :param $extension: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: setContinuousRendering($value)

  :param $value: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isContinuousRendering()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: requestRendering()


 .. php:method:: isFullscreen()

  :returns: :doc:`bool </api_ru/.types/bool>` 



.. include:: /api_ru.desc/php/gdx/Graphics.footer.rst

