Future
---------------------

.. include:: /api_ru.desc/php/concurrent/Future.header.rst

.. php:class:: php\\concurrent\\Future

 Class Future



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: isCancelled()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isDone()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: cancel($mayInterruptIfRunning)

  :param $mayInterruptIfRunning: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: get($timeout = null)

  **throws** :doc:`php\\concurrent\\\\Exception </api_ru/php/concurrent//Exception>`

  :param $timeout: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>`  - - in milliseconds
  :returns: :doc:`mixed </api_ru/.types/mixed>` 



.. include:: /api_ru.desc/php/concurrent/Future.footer.rst

