Semaphore
------------------------

.. include:: /api_en.desc/php/concurrent/Semaphore.header.rst

.. php:class:: php\\concurrent\\Semaphore

 Class Semaphore



**Properties**

----------

 .. php:attr:: fair

  :doc:`bool </api_en/.types/bool>`

  **read-only**


 .. php:attr:: queueLength

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: availablePermits

  :doc:`int </api_en/.types/int>`

  **read-only**


 .. php:attr:: drainPermits

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($permits, $fair = false)

  :param $permits: :doc:`int </api_en/.types/int>` 
  :param $fair: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: acquire($permits = 1, $timeout)

  **throws** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>`

  **throws** :doc:`php\\concurrent\\TimeoutException </api_en/php/concurrent/TimeoutException>`

  :param $permits: :doc:`int </api_en/.types/int>` 
  :param $timeout: :doc:`int </api_en/.types/int>`  - (optional) in millis

 .. php:method:: acquireUninterruptibly($permits = 1, $timeout)

  **throws** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>`

  **throws** :doc:`php\\concurrent\\TimeoutException </api_en/php/concurrent/TimeoutException>`

  :param $permits: :doc:`int </api_en/.types/int>` 
  :param $timeout: :doc:`int </api_en/.types/int>`  - (optional) in millis

 .. php:method:: hasQueuedThreads()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: release($permits = 1)

  :param $permits: :doc:`int </api_en/.types/int>` 

 .. php:method:: tryAcquire($permits = 1)

  :param $permits: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/concurrent/Semaphore.footer.rst

