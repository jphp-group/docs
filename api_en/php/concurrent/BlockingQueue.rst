BlockingQueue
----------------------------

.. include:: /api_en.desc/php/concurrent/BlockingQueue.header.rst

.. php:class:: php\\concurrent\\BlockingQueue

 **extends**: :doc:`php\\util\\Queue </api_en/php/util/Queue>`


 Class BlockingQueue



**Properties**

----------

 .. php:attr:: remainingCapacity

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: __construct($capacity, $fair = false)

  :param $capacity: :doc:`int </api_en/.types/int>` 
  :param $fair: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: take()

  Retrieves and removes the head of this queue, waiting if necessary
  until an element becomes available.

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: put($value)

  Inserts the specified element into this queue, waiting if necessary
  for space to become available.

  :param $value: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: offer($value, $timeout)

  Inserts the specified element into this queue, waiting up to the
  specified wait time if necessary for space to become available.

  **throws** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>`

  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :param $timeout: :doc:`int </api_en/.types/int>`  - (optional) in millis
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: poll($timeout)

  :param $timeout: :doc:`int </api_en/.types/int>`  - in millis
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: drainTo($value, $maxElements)

  Removes all available elements from this queue and adds them
  to the given collection.  This operation may be more
  efficient than repeatedly polling this queue.

  :param $value: :doc:`php\\util\\Collection </api_en/php/util/Collection>` 
  :param $maxElements: :doc:`int </api_en/.types/int>`  - (optional)
  :returns: :doc:`int </api_en/.types/int>` the number of elements transferred



.. include:: /api_en.desc/php/concurrent/BlockingQueue.footer.rst

