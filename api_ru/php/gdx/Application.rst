Application
-------------------

.. include:: /api_ru.desc/php/gdx/Application.header.rst

.. php:class:: php\\gdx\\Application

 **abstract** class

**Children**

----------------------

 * **class** :doc:`php\\gdx\\LwjglApplication </api_ru/php/gdx/LwjglApplication>`



**Constants**

----------

 .. php:const:: LOG_NONE

 .. php:const:: LOG_DEBUG

 .. php:const:: LOG_INFO

 .. php:const:: LOG_ERROR



**Methods**

----------

 .. php:method:: getGraphics()

  :returns: :doc:`php\\gdx\\Graphics </api_ru/php/gdx/Graphics>` 

 .. php:method:: getFiles()

  :returns: :doc:`php\\gdx\\Files </api_ru/php/gdx/Files>` 

 .. php:method:: getInput()

  :returns: :doc:`php\\gdx\\Input </api_ru/php/gdx/Input>` 

 .. php:method:: getAudio()

  :returns: :doc:`php\\gdx\\Audio </api_ru/php/gdx/Audio>` 

 .. php:method:: log($tag, $message)

  :param $tag: :doc:`string </api_ru/.types/string>` 
  :param $message: :doc:`string </api_ru/.types/string>` 

 .. php:method:: error($tag, $message)

  :param $tag: :doc:`string </api_ru/.types/string>` 
  :param $message: :doc:`string </api_ru/.types/string>` 

 .. php:method:: debug($tag, $message)

  :param $tag: :doc:`string </api_ru/.types/string>` 
  :param $message: :doc:`string </api_ru/.types/string>` 

 .. php:method:: setLogLevel($level)

  :param $level: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getLogLevel()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getType()

  :returns: :doc:`string </api_ru/.types/string>` - Android, Desktop, HeadlessDesktop, Applet, WebGL, iOS

 .. php:method:: getVersion()

  :returns: :doc:`int </api_ru/.types/int>` the Android API level on Android, the major OS version on iOS (5, 6, 7, ..), or 0 on the desktop.

 .. php:method:: getJavaHeap()

  :returns: :doc:`int </api_ru/.types/int>` the Java heap memory use in bytes

 .. php:method:: getNativeHeap()

  :returns: :doc:`int </api_ru/.types/int>` the Native heap memory use in bytes

 .. php:method:: halt()


 .. php:method:: getClipboard()

  :returns: :doc:`php\\gdx\\Clipboard </api_ru/php/gdx/Clipboard>` 



.. include:: /api_ru.desc/php/gdx/Application.footer.rst

