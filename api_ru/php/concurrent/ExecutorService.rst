ExecutorService
------------------------------

.. include:: /api_ru.desc/php/concurrent/ExecutorService.header.rst

.. php:class:: php\\concurrent\\ExecutorService

 Класс ExecutorService



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: isScheduled()

  Поставлен в расписание?

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isShutdown()

  Завершен?

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isTerminated()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: execute($runnable, $env = null)

  Выполнить некоторый $runnable через данный сервис

  :param $runnable: :doc:`callable </api_ru/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 

 .. php:method:: submit($runnable, $env = null)

  :param $runnable: :doc:`callable </api_ru/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api_ru/php/concurrent/Future>` 

 .. php:method:: schedule($runnable, $delay, $env = null)

  :param $runnable: :doc:`callable </api_ru/.types/callable>` 
  :param $delay: :doc:`int </api_ru/.types/int>` 
  :param $env: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api_ru/php/concurrent/Future>` 

 .. php:method:: shutdown()


 .. php:method:: shutdownNow()


 .. php:method:: awaitTermination($timeout)

  Блокирует до тех пор пока все задания не будут выполнены после запроса shutdown
  или пока не случится timeout, или текущий поток не будет оборван.

  :param $timeout: :doc:`int </api_ru/.types/int>`  - - in milliseconds
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: newFixedThreadPool($max)

  :param $max: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\concurrent\\ExecutorService </api_ru/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newCachedThreadPool()

  :returns: :doc:`php\\concurrent\\ExecutorService </api_ru/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newSingleThreadExecutor()

  Создает Executor, который будет все обрабатывать в один поток

  :returns: :doc:`php\\concurrent\\ExecutorService </api_ru/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newScheduledThreadPool($corePoolSize)

  Создает пулл потоков, который сможет планировать задания к запуску
  после определенной задержки или для переодического их запуска.

  :param $corePoolSize: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\concurrent\\ExecutorService </api_ru/php/concurrent/ExecutorService>` 



.. include:: /api_ru.desc/php/concurrent/ExecutorService.footer.rst

