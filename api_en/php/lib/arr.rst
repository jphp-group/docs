arr
-----------

.. include:: /api_en.desc/php/lib/arr.header.rst

.. php:class:: php\\lib\\arr

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

 .. php:staticmethod:: has($collection, $value, $strict = false)

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Traversable </api_en/Traversable>` 
  :param $value: :doc:`mixed </api_en/.types/mixed>` 
  :param $strict: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Converts $collection to array

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $withKeys: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: of($collection, $withKeys = false)

  Alias of toArray()

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $withKeys: :doc:`bool </api_en/.types/bool>`, :doc:`php\\lib\\false </api_en/php/lib/false>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: toList($collection)

  Example: items::toList(['x' => 10, 20], 30, ['x' => 50, 60]) -> [10, 20, 30, 50, 60]

  :param $collection: 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: keys($collection)

  Returns all keys of collection

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :returns: :doc:`array </api_en/.types/array>` 

 .. php:staticmethod:: combine($keys, $values)

  Combines two collections to array.

  :param $keys: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $values: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :returns: :doc:`array </api_en/.types/array>`, :doc:`null </api_en/.types/null>` returns null if size of arrays is not equals.

 .. php:staticmethod:: map($collection, $callback)

  :param $collection: :doc:`array </api_en/.types/array>`, :doc:`Iterator </api_en/Iterator>` 
  :param $callback: :doc:`callable </api_en/.types/callable>` 

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

 .. php:staticmethod:: peak($array)

  Returns the last element of array.

  :param $array: 
  :returns: :doc:`mixed </api_en/.types/mixed>` last value of array

 .. php:staticmethod:: push($array, $values)

  :param $array: :doc:`array </api_en/.types/array>`, :doc:`ArrayAccess </api_en/ArrayAccess>` 
  :param $values: 

 .. php:staticmethod:: pop($array)

  :param $array: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: shift($array)

  :param $array: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: unshift($array, $values)

  :param $array: :doc:`array </api_en/.types/array>` 
  :param $values: 

 .. php:staticmethod:: first($collection)

  :param $collection: :doc:`Traversable </api_en/Traversable>`, :doc:`array </api_en/.types/array>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: firstKey($collection)

  :param $collection: :doc:`Traversable </api_en/Traversable>`, :doc:`array </api_en/.types/array>` 
  :returns: :doc:`string </api_en/.types/string>`, :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` 

 .. php:staticmethod:: reverse($array)

  :param $array: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/lib/arr.footer.rst

