ExecutorService
------------------------------

.. php:class:: php\\concurrent\\ExecutorService

 Class ExecutorService
 Класс ExecutorService

 .. php:method:: __construct()

  **private**


 .. php:method:: isScheduled()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isShutdown()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isTerminated()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: execute($runnable, $env = null)

  :param $runnable: :doc:`callable </api/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api/php/lang/Environment>` 

 .. php:method:: submit($runnable, $env = null)

  :param $runnable: :doc:`callable </api/callable>` 
  :param $env: :doc:`php\\lang\\Environment </api/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api/php/concurrent/Future>` 

 .. php:method:: schedule($runnable, $delay, $env = null)

  :param $runnable: :doc:`callable </api/callable>` 
  :param $delay: :doc:`int </api/int>` - milliseconds
  :param $env: :doc:`php\\lang\\Environment </api/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api/php/concurrent/Future>` 

 .. php:method:: shutdown()


 .. php:method:: shutdownNow()


 .. php:method:: awaitTermination($timeout)


  Blocks until all tasks have completed execution after a shutdown
  request, or the timeout occurs, or the current thread is
  interrupted, whichever happens first.

  :param $timeout: :doc:`int </api/int>` - in milliseconds
  :returns: :doc:`bool </api/bool>` 

 .. php:staticmethod:: newFixedThreadPool($max)

  :param $max: 
  :returns: :doc:`php\\concurrent\\ExecutorService </api/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newCachedThreadPool()

  :returns: :doc:`php\\concurrent\\ExecutorService </api/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newSingleThreadExecutor()


  Creates an Executor that uses a single worker thread operating
  off an unbounded queue.

  :returns: :doc:`php\\concurrent\\ExecutorService </api/php/concurrent/ExecutorService>` 

 .. php:staticmethod:: newScheduledThreadPool($corePoolSize)


  Creates a thread pool that can schedule commands to run after a
  given delay, or to execute periodically.

  :param $corePoolSize: 
  :returns: :doc:`php\\concurrent\\ExecutorService </api/php/concurrent/ExecutorService>` 

