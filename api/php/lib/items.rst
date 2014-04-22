items
-------------

.. php:class:: php\\lib\\items

 Library for working with collections - arrays, iterators, etc.
 Библиотека для работы с коллекциями - массивы, итераторы и т.д.
 Class items

 .. php:method:: __construct()

  **private**


 .. php:staticmethod:: count($collection)


  Returns element count of the collection
  .. warning:: for iterators it will iterate all elements to return the result
  Возвращает количество элементов коллекции
  .. warning:: для итераторов для подсчета количества требуется итерация по всем элементам

  :param $collection: 
  :returns: :doc:`int </api/int>` element count количество элементов

 .. php:staticmethod:: each($collection, $callback)


  Iterates all elements of $collection and applies the $callback to each element
  Проходится по всем элементам $collection и применяет $callback к каждому

  :param $collection: 
  :param $callback: :doc:`callable </api/callable>` -> ($value, $key): bool
  to break iteration, return *FALSE* (strongly) from $callback
  чтобы прервать итерацию верните ``false`` (строго) из $callback
  :returns: :doc:`int </api/int>` - iteration count количество итераций

 .. php:staticmethod:: eachSlice($collection, $size, $callback)


  Iterates all elements of $collection with slice $size
  Проходится по всем элементам $collection с учетом среза $size

  :param $collection: 
  :param $size: :doc:`int </api/int>` slice size размер среза
  :param $callback: :doc:`callable </api/callable>` -> (array $slice): bool,
  to break iteration, return ``FALSE`` (strongly) from $callback
  :returns: :doc:`int </api/int>` iteration slice count количество разделенных итераций

 .. php:staticmethod:: find($collection, $callback = null)


  Finds the first value matching the $callback condition
  Находит первый элемент, значение которого удовлетворило условию $callback

  :param $collection: 
  :param $callback: :doc:`callable </api/callable>`, :doc:`null </api/null>` -> ($value, $key): bool
  :returns: :doc:`mixed </api/mixed>`, :doc:`null </api/null>` - null if not found

 .. php:staticmethod:: findAll($collection, $callback = null)


  Finds the all values matching the $callback condition.
  Находит все элементы, значения которых было успешно профильтрованы с помощь $callback

  :param $collection: 
  :param $callback: :doc:`callable </api/callable>` 
  :returns: :doc:`array </api/array>` 

 .. php:staticmethod:: first($collection, $count = 1)


  Returns the first element(s) of $collection
  Возвращает первый элемент(ы) коллекции

  :param $collection: 
  :param $count: 
  :returns: :doc:`array </api/array>`, :doc:`mixed </api/mixed>` returns non-array (one element) if passed $count <= 1

 .. php:staticmethod:: map($collection, $callback)

  :param $collection: 
  :param $callback: :doc:`callable </api/callable>` -> ($value, $key): mixed
  :returns: :doc:`array </api/array>` 

 .. php:staticmethod:: reduce($collection, $callback)


  Combines all elements of $collection by applying a binary operation, specified by a callback
  Сомбинирует все элементы коллекции с применением определенной операции $callback

  :param $collection: 
  :param $callback: :doc:`callable </api/callable>` 
  :returns: :doc:`mixed </api/mixed>`, :doc:`null </api/null>` 

 .. php:staticmethod:: toArray($collection, $withKeys = false)


  Converts $collection to array
  Конвертирует коллекцию в массив

  :param $collection: 
  :param $withKeys: 
  :returns: :doc:`array </api/array>` 

 .. php:staticmethod:: keys($collection)


  Returns all keys of collection
  Возвращает все ключи коллекции

  :param $collection: 
  :returns: :doc:`array </api/array>` 

 .. php:staticmethod:: flatten($collection, $maxLevel = -1)


  Returns a new array that is a one-dimensional flattening of this collection (recursively).
  That is, for every element that is an collection, extract its elements into the new array.
  If the optional $maxLevel argument > -1 the level of recursion to flatten.
  Возвращает новый массив полученный исходя из всех элементов коллекции рекурсивно.

  :param $collection: 
  :param $maxLevel: 
  :returns: :doc:`array </api/array>` 

