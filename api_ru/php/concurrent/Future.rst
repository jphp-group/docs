Future
---------------------

.. php:class:: php\\concurrent\\Future

 Class Future

 .. php:method:: __construct()

  **private**


 .. php:method:: isCancelled()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isDone()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: cancel($mayInterruptIfRunning)

  :param $mayInterruptIfRunning: 
  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: get($timeout = null)

  :param $timeout: :doc:`null </api_ru/null>`, :doc:`int </api_ru/int>` - in milliseconds
  :returns: :doc:`mixed </api_ru/mixed>` 

