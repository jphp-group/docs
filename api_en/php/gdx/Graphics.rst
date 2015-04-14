Graphics
----------------

.. include:: /api_en.desc/php/gdx/Graphics.header.rst

.. php:class:: php\\gdx\\Graphics

 Class Graphics



**Methods**

----------

 .. php:method:: isGL30Available()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getWidth()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getHeight()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDeltaTime()

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: getRawDeltaTime()

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: getFramesPerSecond()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDensity()

  :returns: :doc:`float </api_en/.types/float>` 

 .. php:method:: supportsDisplayModeChange()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDisplayModes()

  :returns: :doc:`php\\gdx\\DisplayMode[] </api_en/php/gdx/DisplayMode>` the supported fullscreen DisplayMode(s)

 .. php:method:: getDesktopDisplayMode()

  :returns: :doc:`php\\gdx\\graphics\\DisplayMode </api_en/php/gdx/graphics/DisplayMode>` 

 .. php:method:: setDisplayMode($widthOrDisplayMode, $height, $fullscreen)

  :param $widthOrDisplayMode: :doc:`php\\gdx\\graphics\\DisplayMode </api_en/php/gdx/graphics/DisplayMode>`, :doc:`int </api_en/.types/int>` 
  :param $height: :doc:`int </api_en/.types/int>`  - (optional)
  :param $fullscreen: :doc:`int </api_en/.types/int>`  - (optional)

 .. php:method:: setTitle($title)

  :param $title: :doc:`string </api_en/.types/string>` 

 .. php:method:: setVSync($vsync)

  :param $vsync: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: supportsExtension($extension)

  :param $extension: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setContinuousRendering($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isContinuousRendering()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: requestRendering()


 .. php:method:: isFullscreen()

  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/gdx/Graphics.footer.rst

