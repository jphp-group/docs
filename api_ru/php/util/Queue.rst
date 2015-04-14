Queue
--------------

.. include:: /api_ru.desc/php/util/Queue.header.rst

.. php:class:: php\\util\\Queue

 **abstract** class

 **extends**: :doc:`php\\util\\Collection </api_ru/php/util/Collection>`

**Children**

----------------------

 * **class** :doc:`php\\concurrent\\BlockingQueue </api_ru/php/concurrent/BlockingQueue>`
 * **class** :doc:`php\\concurrent\\ConcurrentQueue </api_ru/php/concurrent/ConcurrentQueue>`



**Methods**

----------

 .. php:method:: remove($value)

  :param $value: :doc:`mixed </api_ru/.types/mixed>`  - (optional)
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: peek()

  :returns: :doc:`mixed </api_ru/.types/mixed>`, :doc:`null </api_ru/.types/null>` null if queue is empty

 .. php:method:: poll()

  Removes last element and returns it.

  :returns: :doc:`mixed </api_ru/.types/mixed>`, :doc:`null </api_ru/.types/null>` null if queue is empty

 .. php:method:: offer($value)

  Inserts the specified element into this queue
  if it is possible to do so immediately without violating capacity restrictions.
  When using a capacity-restricted queue, this method is generally preferable to add(E),
  which can fail to insert an element only by throwing an exception.

  :param $value: :doc:`mixed </api_ru/.types/mixed>` 
  :returns: :doc:`bool </api_ru/.types/bool>` if the element was added to this queue, else false



.. include:: /api_ru.desc/php/util/Queue.footer.rst

