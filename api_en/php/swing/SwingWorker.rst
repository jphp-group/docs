SwingWorker
---------------------

.. include:: /api_en.desc/php/swing/SwingWorker.header.rst

.. php:class:: php\\swing\\SwingWorker

 **abstract** class




**Methods**

----------

 .. php:method:: doInBackground()

  **abstract**

  **protected**


  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: get($timeout = -1)

  **throws** :doc:`php\\concurrent\\TimeoutException </api_en/php/concurrent/TimeoutException>`

  **throws** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>`

  :param $timeout: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getProgress()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setProgress($val)

  **protected**


  :param $val: :doc:`int </api_en/.types/int>` 

 .. php:method:: publish($values)

  **protected**


  :param $values: :doc:`array </api_en/.types/array>` 

 .. php:method:: process($values)

  **protected**


  :param $values: :doc:`array </api_en/.types/array>` 

 .. php:method:: isDone()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isCanceled()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getState()

  :returns: :doc:`string </api_en/.types/string>` PENDING, STARTED, DONE

 .. php:method:: cancel($mayInterruptIfRunning)

  :param $mayInterruptIfRunning: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: run()


 .. php:method:: execute()




.. include:: /api_en.desc/php/swing/SwingWorker.footer.rst

