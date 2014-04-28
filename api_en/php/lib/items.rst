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

 .. php:staticmethod:: sort($collection, $comparator = null, $saveKeys = false)

  Sorts the specified list into ascending order

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $comparator: :doc:`callable </api_en/.types/callable>`  - ($o1, $o2) -> int where -1 smaller, 0 equal, 1 greater
  :param $saveKeys: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: sortByKeys($collection, $comparator = null, $saveKeys = false)

  Sorts the specified list into ascending order by keys

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $comparator: :doc:`callable </api_en/.types/callable>`  - ($key1, $key2)
  :param $saveKeys: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/lib/items.footer.rst

