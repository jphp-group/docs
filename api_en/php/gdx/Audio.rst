Audio
-------------

.. include:: /api_en.desc/php/gdx/Audio.header.rst

.. php:class:: php\\gdx\\Audio

 Class Audio



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: newAudioDevice($samplingRate, $isMono)

  Creates a new AudioDevice either in mono or stereo mode. The AudioDevice has to be disposed via its
  AudioDevice->dispose() method when it is no longer used.

  **throws** :doc:`php\\gdx\\GdxRuntimeException </api_en/php/gdx/GdxRuntimeException>` in case the device could not be created

  :param $samplingRate: :doc:`int </api_en/.types/int>` 
  :param $isMono: :doc:`boolean </api_en/.types/boolean>` 
  :returns: :doc:`php\\gdx\\audio\\AudioDevice </api_en/php/gdx/audio/AudioDevice>` 

 .. php:method:: newAudioRecorder($samplingRate, $isMono)

  Creates a new AudioRecorder. The AudioRecorder has to be disposed after it is no longer used.

  **throws** :doc:`php\\gdx\\GdxRuntimeException </api_en/php/gdx/GdxRuntimeException>` in case the recorder could not be created

  :param $samplingRate: :doc:`int </api_en/.types/int>` 
  :param $isMono: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`php\\gdx\\audio\\AudioRecorder </api_en/php/gdx/audio/AudioRecorder>` 

 .. php:method:: newSound($fileHandle)

  Creates a new Sound which is used to play back audio effects such as gun shots or explosions. The Sound's audio data
  is retrieved from the file specified via the FileHandle. Note that the complete audio data is loaded into RAM. You
  should therefore not load big audio files with this methods. The current upper limit for decoded audio is 1 MB.
  
  Currently supported formats are WAV, MP3 and OGG.
  
  The Sound has to be disposed if it is no longer used via the {@link Sound#dispose()} method.

  **throws** :doc:`php\\gdx\\GdxRuntimeException </api_en/php/gdx/GdxRuntimeException>` in case the sound could not be loaded

  :param $fileHandle: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 
  :returns: :doc:`php\\gdx\\audio\\Sound </api_en/php/gdx/audio/Sound>` 

 .. php:method:: newMusic($fileHandle)

  Creates a new Music instance which is used to play back a music stream from a file. Currently supported formats are
  WAV, MP3 and OGG. The Music instance has to be disposed if it is no longer used via the Music->dispose() method.
  Music instances are automatically paused when ApplicationListener->pause() is called and resumed when
  ApplicationListener->resume() is called.

  **throws** :doc:`php\\gdx\\GdxRuntimeException </api_en/php/gdx/GdxRuntimeException>` in case the music could not be loaded

  :param $fileHandle: :doc:`php\\gdx\\files\\FileHandle </api_en/php/gdx/files/FileHandle>` 
  :returns: :doc:`php\\gdx\\audio\\Music </api_en/php/gdx/audio/Music>` 



.. include:: /api_en.desc/php/gdx/Audio.footer.rst

