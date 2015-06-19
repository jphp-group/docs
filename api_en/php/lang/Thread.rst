Thread
---------------

.. include:: /api_en.desc/php/lang/Thread.header.rst

.. php:class:: php\\lang\\Thread

 Class Thread



**Constants**

----------

 .. php:const:: MAX_PRIORITY

 .. php:const:: MIN_PRIORITY

 .. php:const:: NORM_PRIORITY



**Methods**

----------

 .. php:method:: __construct($runnable, $env = null, $group = null)

  :param $runnable: :doc:`callable </api_en/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :param $group: :doc:`php\\lang\\ThreadGroup </api_en/php/lang/ThreadGroup>` 

 .. php:method:: getId()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setName($value)

  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getGroup()

  :returns: :doc:`php\\lang\\ThreadGroup </api_en/php/lang/ThreadGroup>` 

 .. php:method:: isDaemon()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setDaemon($value)

  :param $value: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isInterrupted()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAlive()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: start()


 .. php:method:: run()


 .. php:method:: interrupt()


 .. php:method:: join($millis = 0, $nanos = 0)

  Waits at most $millis milliseconds plus
  $nanos nanoseconds for this thread to die.

  :param $millis: :doc:`int </api_en/.types/int>` 
  :param $nanos: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: doYield()


 .. php:staticmethod:: sleep($millis, $nanos = 0)

  Causes the currently executing thread to sleep (temporarily cease
  execution)

  :param $millis: :doc:`int </api_en/.types/int>` 
  :param $nanos: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: getActiveCount()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: current()

  Get current thread

  :returns: :doc:`php\\lang\\Thread </api_en/php/lang/Thread>` 



.. include:: /api_en.desc/php/lang/Thread.footer.rst

