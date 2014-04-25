items
-------------

.. include:: /api_en.desc/php/lib/items.header.rst

.. php:class:: php\\lib\\items

 Library for working with collections - arrays, iterators, etc.



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: count($collection)

  Returns element count of the collection
  
  .. warning:: for iterators it will iterate all elements to return the result

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Countable </api_en/Countable>`, :doc:`Iterator </api_en/Iterator>` 
  :returns: :doc:`int </api_en/.types/int>` element count

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Converts $collection to array

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $withKeys: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: keys($collection)

  Returns all keys of collection

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: flatten($collection, $maxLevel = -1)

  Returns a new array that is a one-dimensional flattening of this collection (recursively).
  That is, for every element that is an collection, extract its elements into the new array.
  If the optional $maxLevel argument > -1 the level of recursion to flatten.

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $maxLevel: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/lib/items.footer.rst

