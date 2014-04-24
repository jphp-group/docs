Thread
---------------

.. include:: /api_ru.desc/php/lang/Thread.header.rst

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

  :param $runnable: :doc:`callable </api_ru/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 
  :param $group: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>` 

 .. php:method:: getId()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: setName($value)

  :param $value: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getGroup()

  :returns: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>` 

 .. php:method:: isDaemon()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: setDaemon($value)

  :param $value: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isInterrupted()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isAlive()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: start()


 .. php:method:: run()


 .. php:method:: interrupt()


 .. php:method:: join($millis = 0, $nanos = 0)

  Waits at most $millis milliseconds plus
  $nanos nanoseconds for this thread to die.

  :param $millis: :doc:`int </api_ru/.types/int>` 
  :param $nanos: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: yield()


 .. php:staticmethod:: sleep($millis, $nanos = 0)

  Causes the currently executing thread to sleep (temporarily cease
  execution)

  :param $millis: :doc:`int </api_ru/.types/int>` 
  :param $nanos: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: getActiveCount()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: current()

  Get current thread

  :returns: :doc:`php\\lang\\Thread </api_ru/php/lang/Thread>` 

 .. php:staticmethod:: sync($object, $runnable)

  :param $object: :doc:`object </api_ru/.types/object>` 
  :param $runnable: :doc:`callable </api_ru/.types/callable>` 



.. include:: /api_ru.desc/php/lang/Thread.footer.rst

