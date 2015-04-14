AudioDevice
-------------------------

.. include:: /api_ru.desc/php/gdx/audio/AudioDevice.header.rst

.. php:class:: php\\gdx\\audio\\AudioDevice

 Class AudioDevice



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: isMono()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: writeSamples($samples, $offset, $numSamples)

  Writes the array of 16-bit signed PCM samples to the audio device and blocks until they have been processed.

  :param $samples: :doc:`array </api_ru/.types/array>` 
  :param $offset: :doc:`int </api_ru/.types/int>` 
  :param $numSamples: :doc:`int </api_ru/.types/int>` 

 .. php:method:: writeFloatSamples($samples, $offset, $numSamples)

  Writes the array of float PCM samples to the audio device and blocks until they have been processed.

  :param $samples: :doc:`array </api_ru/.types/array>` 
  :param $offset: :doc:`int </api_ru/.types/int>` 
  :param $numSamples: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getLatency()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: dispose()


 .. php:method:: setVolume($volume)

  Sets the volume in the range [0,1].

  :param $volume: :doc:`double </api_ru/.types/double>` 



.. include:: /api_ru.desc/php/gdx/audio/AudioDevice.footer.rst

