SharedMemory
---------------------

.. include:: /api_en.desc/php/util/SharedMemory.header.rst

.. php:class:: php\\util\\SharedMemory

 **abstract** class

**Children**

----------------------

 * **abstract** **class** :doc:`php\\util\\SharedCollection </api_en/php/util/SharedCollection>`
 * **class** :doc:`php\\util\\SharedValue </api_en/php/util/SharedValue>`



**Methods**

----------

 .. php:method:: synchronize($callback)

  You can use a shared value as a mutex

  :param $callback: :doc:`callable </api_en/.types/callable>`  - (SharedValue $this)
  :returns: :doc:`mixed </api_en/.types/mixed>` result of execution of $callback



.. include:: /api_en.desc/php/util/SharedMemory.footer.rst

