items
-------------

.. php:class:: php\\lib\\items

 Библиотека для работы с коллекциями - массивы, итераторы и т.д.
 Class items

 .. php:method:: __construct()

  **private**


 .. php:staticmethod:: count($collection)

  Возвращает количество элементов коллекции
  .. warning:: для итераторов для подсчета количества требуется итерация по всем элементам

  :param $collection: 
  :returns: :doc:`int </api_ru/int>` количество элементов

 .. php:staticmethod:: each($collection, $callback)

  Проходится по всем элементам $collection и применяет $callback к каждому

  :param $collection: 
  :param $callback: :doc:`callable </api_ru/callable>` чтобы прервать итерацию верните ``false`` (строго) из $callback
  :returns: :doc:`int </api_ru/int>` количество итераций

 .. php:staticmethod:: eachSlice($collection, $size, $callback)

  Проходится по всем элементам $collection с учетом среза $size

  :param $collection: 
  :param $size: :doc:`int </api_ru/int>` размер среза
  :param $callback: :doc:`callable </api_ru/callable>` -> (array $slice): bool,
  to break iteration, return ``FALSE`` (strongly) from $callback
  :returns: :doc:`int </api_ru/int>` количество разделенных итераций

 .. php:staticmethod:: find($collection, $callback = null)

  Находит первый элемент, значение которого удовлетворило условию $callback

  :param $collection: 
  :param $callback: :doc:`callable </api_ru/callable>`, :doc:`null </api_ru/null>` -> ($value, $key): bool
  :returns: :doc:`mixed </api_ru/mixed>`, :doc:`null </api_ru/null>` - null if not found

 .. php:staticmethod:: findAll($collection, $callback = null)

  Находит все элементы, значения которых было успешно профильтрованы с помощь $callback

  :param $collection: 
  :param $callback: :doc:`callable </api_ru/callable>` 
  :returns: :doc:`array </api_ru/array>` 

 .. php:staticmethod:: first($collection, $count = 1)

  Возвращает первый элемент(ы) коллекции

  :param $collection: 
  :param $count: 
  :returns: :doc:`array </api_ru/array>`, :doc:`mixed </api_ru/mixed>` returns non-array (one element) if passed $count <= 1

 .. php:staticmethod:: map($collection, $callback)

  :param $collection: 
  :param $callback: :doc:`callable </api_ru/callable>` -> ($value, $key): mixed
  :returns: :doc:`array </api_ru/array>` 

 .. php:staticmethod:: reduce($collection, $callback)

  Сомбинирует все элементы коллекции с применением определенной операции $callback

  :param $collection: 
  :param $callback: :doc:`callable </api_ru/callable>` 
  :returns: :doc:`mixed </api_ru/mixed>`, :doc:`null </api_ru/null>` 

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Конвертирует коллекцию в массив

  :param $collection: 
  :param $withKeys: 
  :returns: :doc:`array </api_ru/array>` 

 .. php:staticmethod:: keys($collection)

  Возвращает все ключи коллекции

  :param $collection: 
  :returns: :doc:`array </api_ru/array>` 

 .. php:staticmethod:: flatten($collection, $maxLevel = -1)

  Возвращает новый массив полученный исходя из всех элементов коллекции рекурсивно.

  :param $collection: 
  :param $maxLevel: 
  :returns: :doc:`array </api_ru/array>` 

