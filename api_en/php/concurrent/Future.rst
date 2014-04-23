Future
---------------------

.. include:: /api_en.desc/php/concurrent/Future.header.rst

.. php:class:: php\\concurrent\\Future

 Class Future



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: isCancelled()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isDone()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: cancel($mayInterruptIfRunning)

  :param $mayInterruptIfRunning: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: get($timeout = null)

  :param $timeout: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` - in milliseconds
  :returns: :doc:`mixed </api_en/.types/mixed>` 



.. include:: /api_en.desc/php/concurrent/Future.footer.rst

