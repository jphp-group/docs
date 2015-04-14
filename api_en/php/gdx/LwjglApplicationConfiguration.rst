LwjglApplicationConfiguration
-------------------------------------

.. include:: /api_en.desc/php/gdx/LwjglApplicationConfiguration.header.rst

.. php:class:: php\\gdx\\LwjglApplicationConfiguration

 Class ApplicationConfiguration



**Properties**

----------

 .. php:attr:: useGL30

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: depth

  :doc:`int </api_en/.types/int>`

 .. php:attr:: samples

  :doc:`int </api_en/.types/int>`

 .. php:attr:: width

  :doc:`int </api_en/.types/int>`

 .. php:attr:: height

  :doc:`int </api_en/.types/int>`

 .. php:attr:: x

  :doc:`int </api_en/.types/int>`

 .. php:attr:: y

  :doc:` </api_en/.types/>`

 .. php:attr:: fullscreen

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: vSyncEnabled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: title

  :doc:`string </api_en/.types/string>`

 .. php:attr:: forceExit

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: resizable

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: audioDeviceSimultaneousSources

  :doc:`int </api_en/.types/int>`

 .. php:attr:: audioDeviceBufferSize

  :doc:`int </api_en/.types/int>`

 .. php:attr:: audioDeviceBufferCount

  :doc:`int </api_en/.types/int>`

 .. php:attr:: foregroundFPS

  :doc:`int </api_en/.types/int>`

 .. php:attr:: backgroundFPS

  :doc:`int </api_en/.types/int>`

 .. php:attr:: allowSoftwareMode

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: preferencesDirectory

  :doc:`string </api_en/.types/string>`



**Methods**

----------

 .. php:method:: setFromDisplayMode($displayMode)

  :param $displayMode: :doc:`php\\gdx\\graphics\\DisplayMode </api_en/php/gdx/graphics/DisplayMode>` 

 .. php:staticmethod:: getDesktopDisplayMode()

  :returns: :doc:`php\\gdx\\graphics\\DisplayMode </api_en/php/gdx/graphics/DisplayMode>` 

 .. php:staticmethod:: getDisplayModes()

  :returns: :doc:`php\\gdx\\DisplayMode[] </api_en/php/gdx/DisplayMode>` 

 .. php:staticmethod:: addIcon($path, $type)

  Adds a window icon. Icons are tried in the order added, the first one that works is used. Typically three icons should be
  provided: 128x128 (for Mac), 32x32 (for Windows and Linux), and 16x16 (for Windows).

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $type: :doc:`string </api_en/.types/string>`  - - Classpath, Internal, External, Absolute, Local



.. include:: /api_en.desc/php/gdx/LwjglApplicationConfiguration.footer.rst

