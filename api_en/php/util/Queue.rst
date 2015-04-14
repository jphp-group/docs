Queue
--------------

.. include:: /api_en.desc/php/util/Queue.header.rst

.. php:class:: php\\util\\Queue

 **abstract** class

 **extends**: :doc:`php\\util\\Collection </api_en/php/util/Collection>`

**Children**

----------------------

 * **class** :doc:`php\\concurrent\\BlockingQueue </api_en/php/concurrent/BlockingQueue>`
 * **class** :doc:`php\\concurrent\\ConcurrentQueue </api_en/php/concurrent/ConcurrentQueue>`



**Methods**

----------

 .. php:method:: remove($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>`  - (optional)
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: peek()

  :returns: :doc:`mixed </api_en/.types/mixed>`, :doc:`null </api_en/.types/null>` null if queue is empty

 .. php:method:: poll()

  Removes last element and returns it.

  :returns: :doc:`mixed </api_en/.types/mixed>`, :doc:`null </api_en/.types/null>` null if queue is empty

 .. php:method:: offer($value)

  Inserts the specified element into this queue
  if it is possible to do so immediately without violating capacity restrictions.
  When using a capacity-restricted queue, this method is generally preferable to add(E),
  which can fail to insert an element only by throwing an exception.

  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :returns: :doc:`bool </api_en/.types/bool>` if the element was added to this queue, else false



.. include:: /api_en.desc/php/util/Queue.footer.rst

