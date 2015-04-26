SharedQueue
--------------------

.. include:: /api_en.desc/php/util/SharedQueue.header.rst

.. php:class:: php\\util\\SharedQueue

 **extends**: :doc:`php\\util\\SharedCollection </api_en/php/util/SharedCollection>`


 Class SharedQueue



**Methods**

----------

 .. php:method:: __construct($array)

  :param $array: :doc:`array </api_en/.types/array>`, :doc:`Traversable </api_en/Traversable>`  - (optional)

 .. php:method:: isEmpty()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: count()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: clear()

  Remove all elements.

  :returns: :doc:`void </api_en/.types/void>` 

 .. php:method:: add($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: peek()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: poll()

  Retrieves and removes the head of this queue.

  :returns: :doc:`mixed </api_en/.types/mixed>` 



.. include:: /api_en.desc/php/util/SharedQueue.footer.rst

