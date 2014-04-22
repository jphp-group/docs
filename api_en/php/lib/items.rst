items
-------------

.. php:class:: php\\lib\\items

 Library for working with collections - arrays, iterators, etc.

 .. php:method:: __construct()

  **private**


 .. php:staticmethod:: count($collection)

  Returns element count of the collection
  .. warning:: for iterators it will iterate all elements to return the result

  :param $collection: 
  :returns: :doc:`int </api_en/int>` element count

 .. php:staticmethod:: each($collection, $callback)

  Iterates all elements of $collection and applies the $callback to each element

  :param $collection: 
  :param $callback: :doc:`callable </api_en/callable>` -> ($value, $key): bool
  to break iteration, return *FALSE* (strongly) from $callback
  :returns: :doc:`int </api_en/int>` - iteration count

 .. php:staticmethod:: eachSlice($collection, $size, $callback)

  Iterates all elements of $collection with slice $size

  :param $collection: 
  :param $size: :doc:`int </api_en/int>` slice size
  :param $callback: :doc:`callable </api_en/callable>` -> (array $slice): bool,
  to break iteration, return ``FALSE`` (strongly) from $callback
  :returns: :doc:`int </api_en/int>` iteration slice count

 .. php:staticmethod:: find($collection, $callback = null)

  Finds the first value matching the $callback condition

  :param $collection: 
  :param $callback: :doc:`callable </api_en/callable>`, :doc:`null </api_en/null>` -> ($value, $key): bool
  :returns: :doc:`mixed </api_en/mixed>`, :doc:`null </api_en/null>` - null if not found

 .. php:staticmethod:: findAll($collection, $callback = null)

  Finds the all values matching the $callback condition.

  :param $collection: 
  :param $callback: :doc:`callable </api_en/callable>` 
  :returns: :doc:`array </api_en/array>` 

 .. php:staticmethod:: first($collection, $count = 1)

  Returns the first element(s) of $collection

  :param $collection: 
  :param $count: 
  :returns: :doc:`array </api_en/array>`, :doc:`mixed </api_en/mixed>` returns non-array (one element) if passed $count <= 1

 .. php:staticmethod:: map($collection, $callback)

  :param $collection: 
  :param $callback: :doc:`callable </api_en/callable>` -> ($value, $key): mixed
  :returns: :doc:`array </api_en/array>` 

 .. php:staticmethod:: reduce($collection, $callback)

  Combines all elements of $collection by applying a binary operation, specified by a callback

  :param $collection: 
  :param $callback: :doc:`callable </api_en/callable>` 
  :returns: :doc:`mixed </api_en/mixed>`, :doc:`null </api_en/null>` 

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Converts $collection to array

  :param $collection: 
  :param $withKeys: 
  :returns: :doc:`array </api_en/array>` 

 .. php:staticmethod:: keys($collection)

  Returns all keys of collection

  :param $collection: 
  :returns: :doc:`array </api_en/array>` 

 .. php:staticmethod:: flatten($collection, $maxLevel = -1)

  Returns a new array that is a one-dimensional flattening of this collection (recursively).
  That is, for every element that is an collection, extract its elements into the new array.
  If the optional $maxLevel argument > -1 the level of recursion to flatten.

  :param $collection: 
  :param $maxLevel: 
  :returns: :doc:`array </api_en/array>` 

