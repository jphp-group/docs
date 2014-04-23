Timer
---------------

.. include:: /api_en.desc/php/swing/Timer.header.rst

.. php:class:: php\\swing\\Timer



**Properties**

----------

 .. php:attr:: repeat

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: delay

  :doc:`int </api_en/.types/int>`

  Delay in milliseconds for repeats

 .. php:attr:: initDelay

  :doc:`int </api_en/.types/int>`

  Initial Delay in milliseconds for first trigger

 .. php:attr:: actionCommand

  :doc:`string </api_en/.types/string>`

  User data



**Methods**

----------

 .. php:method:: __construct($delay, $callback)

  :param $delay: 
  :param $callback: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: start()


 .. php:method:: stop()


 .. php:method:: restart()


 .. php:method:: isRunning()

  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/swing/Timer.footer.rst

