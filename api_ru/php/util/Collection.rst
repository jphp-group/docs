Collection
-------------------

.. include:: /api_ru.desc/php/util/Collection.header.rst

.. php:class:: php\\util\\Collection

 **abstract** class

 **implements**: :doc:`Countable </api_ru/Countable>`, :doc:`Iterator </api_ru/Iterator>`

**Children**

----------------------

 * **abstract** **class** :doc:`php\\util\\Queue </api_ru/php/util/Queue>`



**Properties**

----------

 .. php:attr:: empty

  :doc:`bool </api_ru/.types/bool>`

  **read-only**




**Methods**

----------

 .. php:method:: add($value)

  :param $value: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: addAll($value)

  :param $value: :doc:`Traversable </api_ru/Traversable>`, :doc:`array </api_ru/.types/array>` 

 .. php:method:: remove($value)

  :param $value: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: clear()


 .. php:method:: count()

  {@inheritdoc}

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isEmpty()

  **protected**


  Getter of empty property

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: current()


 .. php:method:: next()


 .. php:method:: key()


 .. php:method:: valid()


 .. php:method:: rewind()




.. include:: /api_ru.desc/php/util/Collection.footer.rst

