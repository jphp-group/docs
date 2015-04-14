Lock
-------------------

.. include:: /api_en.desc/php/concurrent/Lock.header.rst

.. php:class:: php\\concurrent\\Lock

 Class Lock



**Methods**

----------

 .. php:method:: __construct($fair = false)

  :param $fair: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: lock()


 .. php:method:: lockInterruptibly()

  **throws** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>` if the current thread is
  interrupted while acquiring the lock (and interruption
  of lock acquisition is supported).


 .. php:method:: tryLock($timeout)

  Acquires the lock only if it is free at the time of invocation.

  :param $timeout: :doc:`int </api_en/.types/int>`  - (optional) in millis
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: unlock()




.. include:: /api_en.desc/php/concurrent/Lock.footer.rst

