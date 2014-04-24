Timer
---------------

.. include:: /api_ru.desc/php/swing/Timer.header.rst

.. php:class:: php\\swing\\Timer



**Properties**

----------

 .. php:attr:: repeat

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: delay

  :doc:`int </api_ru/.types/int>`

  Delay in milliseconds for repeats

 .. php:attr:: initDelay

  :doc:`int </api_ru/.types/int>`

  Initial Delay in milliseconds for first trigger

 .. php:attr:: actionCommand

  :doc:`string </api_ru/.types/string>`

  User data



**Methods**

----------

 .. php:method:: __construct($delay, $callback)

  :param $delay: :doc:`int </api_ru/.types/int>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>` 

 .. php:method:: start()


 .. php:method:: stop()


 .. php:method:: restart()


 .. php:method:: isRunning()

  :returns: :doc:`bool </api_ru/.types/bool>` 



.. include:: /api_ru.desc/php/swing/Timer.footer.rst

