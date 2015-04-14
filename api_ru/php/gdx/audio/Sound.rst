Sound
-------------------

.. include:: /api_ru.desc/php/gdx/audio/Sound.header.rst

.. php:class:: php\\gdx\\audio\\Sound

 Class Sound



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: play($volume, $pitch, $pan)

  Plays the sound. If the sound is already playing, it will be played again, concurrently.

  :param $volume: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $pitch: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $pan: :doc:`double </api_ru/.types/double>`  - (optional)
  :returns: :doc:`int </api_ru/.types/int>` the id of the sound instance if successful, or -1 on failure.

 .. php:method:: loop($volume, $pitch, $pan)

  Plays the sound, looping. If the sound is already playing, it will be played again, concurrently.
  You need to stop the sound via a call to stop(long) using the returned id.

  :param $volume: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $pitch: :doc:`double </api_ru/.types/double>`  - (optional)
  :param $pan: :doc:`double </api_ru/.types/double>`  - (optional)
  :returns: :doc:`int </api_ru/.types/int>` the id of the sound instance if successful, or -1 on failure.

 .. php:method:: stop($soundId)

  Stops playing all or $soundId instance(s) of this sound.

  :param $soundId: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: pause($soundId)

  Pauses the sound instance with the given id as returned by play() or all sounds. If the sound is no
  longer playing, this has no effect.

  :param $soundId: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: resume($soundId)

  :param $soundId: :doc:`int </api_ru/.types/int>`  - (optional)

 .. php:method:: setLooping($soundId, $looping)

  Sets the sound instance with the given id to be looping. If the sound is no longer playing this has no effect

  :param $soundId: :doc:`int </api_ru/.types/int>` 
  :param $looping: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: setPitch($soundId, $pitch)

  Changes the pitch multiplier of the sound instance with the given id as returned by play().
  If the sound is no longer playing, this has no effect.

  :param $soundId: :doc:`int </api_ru/.types/int>` 
  :param $pitch: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setPan($soundId, $pan, $volume)

  Sets the panning and volume of the sound instance with the given id as returned by play().
  If the sound is no longer playing, this has no effect.

  :param $soundId: :doc:`int </api_ru/.types/int>` 
  :param $pan: :doc:`float </api_ru/.types/float>` 
  :param $volume: :doc:`float </api_ru/.types/float>` 

 .. php:method:: setPriority($soundId, $priority)

  Sets the priority of a sound currently being played back. Higher priority sounds will be considered last if the maximum
  number of concurrently playing sounds is exceeded. This is only a hint and might not be honored by a backend implementation.

  :param $soundId: :doc:`int </api_ru/.types/int>` 
  :param $priority: :doc:`int </api_ru/.types/int>`  - the priority (0 == lowest)

 .. php:method:: dispose()




.. include:: /api_ru.desc/php/gdx/audio/Sound.footer.rst

