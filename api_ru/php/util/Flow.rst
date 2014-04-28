Flow
-------------

.. include:: /api_ru.desc/php/util/Flow.header.rst

.. php:class:: php\\util\\Flow

 **implements**: :doc:`Iterator </api_ru/Iterator>`


 A special class to work with arrays and iterators under flows.
 Flows are used for the lazy array/iterator operations, to save the RAM memory.
 
 Class Flow, Immutable



**Methods**

----------

 .. php:method:: __construct($collection)

  Create a new flow, you can also use ``of()`` method

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 

 .. php:method:: withKeys()

  Enables to save keys for the next operation

  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: append($collection)

  Appends a new collection to the current flow,
  do not remember that you can pass a flow to this method

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: find($filter = null)

  Finds elements by using the $filter callback,
  elements - for each iteration that returns ``true``

  :param $filter: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: findOne($filter = null)

  Finds the first element by using the $filter callback,
  when $filter will return the first ``true``

  :param $filter: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: group($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: each($callback)

  Iterates elements.
  It will break if $callback returns ``false`` strongly

  :param $callback: :doc:`callable </api_ru/.types/callable>`  - ($el[, $key]): bool
  :returns: :doc:`int </api_ru/.types/int>` - iteration count

 .. php:method:: eachSlice($sliceSize, $callback, $withKeys = false)

  Iterates elements as slices (that are passing as arrays to $callback).
  It will break if $callback returns ``false`` strongly

  :param $sliceSize: :doc:`int </api_ru/.types/int>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>`  - (array $items): bool
  :param $withKeys: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`int </api_ru/.types/int>` - slice iteration count

 .. php:method:: map($callback)

  Iterates elements and returns a new flow of the result
  Example::
  
  $newFlow = Flow::of([1,2,3])->map(function($el){  return $el * 10 });
  // the new flow will contain 10, 20 and 30

  :param $callback: :doc:`callable </api_ru/.types/callable>`  - ($el[, $key])
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: keys()

  Create a new flow by using the keys of the current flow

  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: skip($n)

  Skips $n elements in the current collection

  :param $n: :doc:`int </api_ru/.types/int>`  - skip count
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: limit($count)

  Limits collection with $count

  :param $count: :doc:`int </api_ru/.types/int>`  - count of limit
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: reduce($callback)

  Iterates elements and gets a result of this operation
  It can be used for calculate some results, for example::
  
  // calculates a sum of elements
  $sum = .. ->reduce(function($result, $el){  $result = $result + $el });

  :param $callback: :doc:`callable </api_ru/.types/callable>`  - ($result, $el[, $key])
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: sort($comparator = null)

  Sort the last result of the flow, also see: ``php\\lib\\items::sort()``
  
  .. note:: use the ``withKeys()`` method to save keys

  :param $comparator: :doc:`callable </api_ru/.types/callable>`  - ($o1, $o2) -> int, where -1 smaller, 0 equal, 1 greater
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:method:: sortByKeys($comparator = null)

  The same method as ``sort()`` only based on keys insteadof values
  
  .. note:: use the ``withKeys()`` method to save keys

  :param $comparator: :doc:`callable </api_ru/.types/callable>`  - ($key1, $key2) -> int
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:method:: toArray()

  Convert elements to an array
  
  .. note:: use the ``withKeys()`` method to save keys

  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:method:: toString($separator)

  Join elements to a string similar to ``implode()`` in PHP

  :param $separator: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: count()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: current()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: next()

  :returns: :doc:`void </api_ru/.types/void>` 

 .. php:method:: key()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: rewind()

  :returns: :doc:`void </api_ru/.types/void>` 

 .. php:method:: __clone()

  **private**



 .. php:staticmethod:: of($collection)

  Creates a new flow for an array of Iterator

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`php\\util\\\\Iterator </api_ru/php/util//Iterator>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:staticmethod:: ofRange($from, $to, $step = 1)

  Creates a new flow for a number range

  :param $from: :doc:`int </api_ru/.types/int>` 
  :param $to: :doc:`int </api_ru/.types/int>` 
  :param $step: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:staticmethod:: ofString($string, $chunkSize = 1)

  Creates a new flow for the string

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $chunkSize: :doc:`int </api_ru/.types/int>`  - how many characters to combine for one item ?
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:staticmethod:: ofStream($stream, $chunkSize = 1)

  Creates a new flow for the Stream object

  :param $stream: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`  - stream object
  :param $chunkSize: :doc:`int </api_ru/.types/int>`  - size for ``Stream.read($size)`` method
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 



.. include:: /api_ru.desc/php/util/Flow.footer.rst

