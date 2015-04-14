AudioRecorder
---------------------------

.. include:: /api_ru.desc/php/gdx/audio/AudioRecorder.header.rst

.. php:class:: php\\gdx\\audio\\AudioRecorder

 Class AudioRecorder



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: read($samples, $offset, $numSamples)

  Reads in numSamples samples into the array samples starting at offset. If the recorder is in stereo you have to multiply
  numSamples by 2.

  :param $samples: :doc:`array </api_ru/.types/array>` 
  :param $offset: :doc:`int </api_ru/.types/int>` 
  :param $numSamples: :doc:`int </api_ru/.types/int>` 

 .. php:method:: dispose()




.. include:: /api_ru.desc/php/gdx/audio/AudioRecorder.footer.rst

