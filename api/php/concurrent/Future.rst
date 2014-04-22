Future
---------------------

.. php:class:: php\\concurrent\\Future

 Class Future

 .. php:method:: __construct()

  **private**


 .. php:method:: isCancelled()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isDone()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: cancel($mayInterruptIfRunning)

  :param $mayInterruptIfRunning: 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: get($timeout = null)

  :param $timeout: :doc:`null </api/null>`, :doc:`int </api/int>` - in milliseconds
  :returns: :doc:`mixed </api/mixed>` 

