ExecutorService
------------------------------

.. include:: /api_en.desc/php/concurrent/ExecutorService.header.rst

.. php:class:: php\\concurrent\\ExecutorService

 Class ExecutorService



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: isScheduled()

  Is Scheduled ?

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isShutdown()

  Is Shutdown?

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isTerminated()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: execute($runnable, $env = null)

  Execute some $runnable via the Executor Service

  :param $runnable: :doc:`callable </api_en/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 

 .. php:method:: submit($runnable, $env = null)

  :param $runnable: :doc:`callable </api_en/.types/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api_en/php/concurrent/Future>` 

 .. php:method:: schedule($runnable, $delay, $env = null)

  :param $runnable: :doc:`callable </api_en/.types/callable>` 
  :param $delay: :doc:`int </api_en/.types/int>` - milliseconds
  :param $env: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api_en/php/concurrent/Future>` 

 .. php:method:: shutdown()


 .. php:method:: shutdownNow()


 .. php:method:: awaitTermination($timeout)

  Blocks until all tasks have completed execution after a shutdown
  request, or the timeout occurs, or the current thread is
  interrupted, whichever happens first.

  :param $timeout: :doc:`int </api_en/.types/int>` - in milliseconds
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: newFixedThreadPool($max)

  :param $max: 
  :returns: :doc:`php\\concurrent\\ExecutorService </api_en/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newCachedThreadPool()

  :returns: :doc:`php\\concurrent\\ExecutorService </api_en/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newSingleThreadExecutor()

  Creates an Executor that uses a single worker thread operating
  off an unbounded queue.

  :returns: :doc:`php\\concurrent\\ExecutorService </api_en/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newScheduledThreadPool($corePoolSize)

  Creates a thread pool that can schedule commands to run after a
  given delay, or to execute periodically.

  :param $corePoolSize: 
  :returns: :doc:`php\\concurrent\\ExecutorService </api_en/php/concurrent/ExecutorService>` 



.. include:: /api_en.desc/php/concurrent/ExecutorService.footer.rst

