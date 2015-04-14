Collection
-------------------

.. include:: /api_en.desc/php/util/Collection.header.rst

.. php:class:: php\\util\\Collection

 **abstract** class

 **implements**: :doc:`Countable </api_en/Countable>`, :doc:`Iterator </api_en/Iterator>`

**Children**

----------------------

 * **abstract** **class** :doc:`php\\util\\Queue </api_en/php/util/Queue>`



**Properties**

----------

 .. php:attr:: empty

  :doc:`bool </api_en/.types/bool>`

  **read-only**




**Methods**

----------

 .. php:method:: add($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: addAll($value)

  :param $value: :doc:`Traversable </api_en/Traversable>`, :doc:`array </api_en/.types/array>` 

 .. php:method:: remove($value)

  :param $value: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: clear()


 .. php:method:: count()

  {@inheritdoc}

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: isEmpty()

  **protected**


  Getter of empty property

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: current()


 .. php:method:: next()


 .. php:method:: key()


 .. php:method:: valid()


 .. php:method:: rewind()




.. include:: /api_en.desc/php/util/Collection.footer.rst

