SharedCollection
-------------------------

.. include:: /api_en.desc/php/util/SharedCollection.header.rst

.. php:class:: php\\util\\SharedCollection

 **abstract** class

 **extends**: :doc:`php\\util\\SharedMemory </api_en/php/util/SharedMemory>`

 **implements**: :doc:`Countable </api_en/Countable>`, :doc:`Traversable </api_en/Traversable>`

**Children**

----------------------

 * **class** :doc:`php\\util\\SharedMap </api_en/php/util/SharedMap>`
 * **class** :doc:`php\\util\\SharedQueue </api_en/php/util/SharedQueue>`
 * **class** :doc:`php\\util\\SharedStack </api_en/php/util/SharedStack>`



**Methods**

----------

 .. php:method:: isEmpty()

  **abstract**


  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: count()

  **abstract**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: clear()

  **abstract**


  Remove all elements.

  :returns: :doc:`void </api_en/.types/void>` 



.. include:: /api_en.desc/php/util/SharedCollection.footer.rst

