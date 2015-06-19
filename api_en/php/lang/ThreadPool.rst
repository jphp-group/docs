ThreadPool
-------------------

.. include:: /api_en.desc/php/lang/ThreadPool.header.rst

.. php:class:: php\\lang\\ThreadPool

 Class ThreadPool



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
  :param $delay: :doc:`int </api_en/.types/int>` 
  :param $env: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :returns: :doc:`php\\concurrent\\Future </api_en/php/concurrent/Future>` 

 .. php:method:: shutdown()


 .. php:method:: shutdownNow()


 .. php:method:: awaitTermination($timeout)

  Blocks until all tasks have completed execution after a shutdown
  request, or the timeout occurs, or the current thread is
  interrupted, whichever happens first.

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>`

  :param $timeout: :doc:`int </api_en/.types/int>`  - - in milliseconds
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: create($coreSize, $maxSize, $keepAliveTime = 0)

  :param $coreSize: :doc:`int </api_en/.types/int>`  - the number of threads to keep in the pool, even if they are idle
  :param $maxSize: :doc:`int </api_en/.types/int>`  - the maximum number of threads to allow in the pool
  :param $keepAliveTime: :doc:`int </api_en/.types/int>`  - in millis
  :returns: :doc:`php\\lang\\ThreadPool </api_en/php/lang/ThreadPool>` 

 .. php:staticmethod:: createFixed($max)

  :param $max: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\lang\\ThreadPool </api_en/php/lang/ThreadPool>` 

 .. php:staticmethod:: createCached()

  :returns: :doc:`php\\lang\\ThreadPool </api_en/php/lang/ThreadPool>` 

 .. php:staticmethod:: createSingle()

  Creates an Executor that uses a single worker thread operating
  off an unbounded queue.

  :returns: :doc:`php\\lang\\ThreadPool </api_en/php/lang/ThreadPool>` 

 .. php:staticmethod:: createScheduled($corePoolSize)

  Creates a thread pool that can schedule commands to run after a
  given delay, or to execute periodically.

  :param $corePoolSize: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\lang\\ThreadPool </api_en/php/lang/ThreadPool>` 



.. include:: /api_en.desc/php/lang/ThreadPool.footer.rst

