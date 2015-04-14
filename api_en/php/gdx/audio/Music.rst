Music
-------------------

.. include:: /api_en.desc/php/gdx/audio/Music.header.rst

.. php:class:: php\\gdx\\audio\\Music

 Class Music



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: play()


 .. php:method:: pause()


 .. php:method:: stop()


 .. php:method:: isPlaying()

  :returns: :doc:`bool </api_en/.types/bool>` whether this music stream is playing

 .. php:method:: setLooping($isLooping)

  :param $isLooping: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isLooping()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setVolume($volume)

  :param $volume: :doc:`double </api_en/.types/double>` 

 .. php:method:: getVolume()

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: setPan($pan, $volume)

  Sets the panning and volume of this music stream.

  :param $pan: :doc:`double </api_en/.types/double>`  - panning in the range -1 (full left) to 1 (full right). 0 is center position.
  :param $volume: :doc:`double </api_en/.types/double>` 

 .. php:method:: getPosition()

  Returns the playback position in milliseconds.

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: dispose()


 .. php:method:: setOnCompletionListener($listener)

  Register a callback to be invoked when the end of a music stream has been reached during playback.

  :param $listener: :doc:`callable </api_en/.types/callable>`  - (Music $music)



.. include:: /api_en.desc/php/gdx/audio/Music.footer.rst

