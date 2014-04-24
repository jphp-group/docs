items
-------------

.. include:: /api_ru.desc/php/lib/items.header.rst

.. php:class:: php\\lib\\items

 Библиотека для работы с коллекциями - массивы, итераторы и т.д.
 
 Class items



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: count($collection)

  Возвращает количество элементов коллекции
  
  .. warning:: для итераторов для подсчета количества требуется итерация по всем элементам

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Countable </api_ru/Countable>`, :doc:`Iterator </api_ru/Iterator>` 
  :returns: :doc:`int </api_ru/.types/int>` количество элементов

 .. php:staticmethod:: each($collection, $callback)

  Проходится по всем элементам $collection и применяет $callback к каждому

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>`  - чтобы прервать итерацию верните ``false`` (строго) из $callback
  :returns: :doc:`int </api_ru/.types/int>` количество итераций

 .. php:staticmethod:: eachSlice($collection, $size, $callback)

  Проходится по всем элементам $collection с учетом среза $size

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $size: :doc:`int </api_ru/.types/int>`  - размер среза
  :param $callback: :doc:`callable </api_ru/.types/callable>`  - -> (array $slice): bool,
  to break iteration, return ``FALSE`` (strongly) from $callback
  :returns: :doc:`int </api_ru/.types/int>` количество разделенных итераций

 .. php:staticmethod:: find($collection, $callback = null)

  Находит первый элемент, значение которого удовлетворило условию $callback

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>`  - -> ($value, $key): bool
  :returns: :doc:`mixed </api_ru/.types/mixed>`, :doc:`null </api_ru/.types/null>` - null if not found

 .. php:staticmethod:: findAll($collection, $callback = null)

  Находит все элементы, значения которых было успешно профильтрованы с помощь $callback

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: first($collection, $count = 1)

  Возвращает первый элемент(ы) коллекции

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $count: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`array </api_ru/.types/array>`, :doc:`mixed </api_ru/.types/mixed>` returns non-array (one element) if passed $count <= 1

 .. php:staticmethod:: map($collection, $callback)

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>`  - -> ($value, $key): mixed
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: reduce($collection, $callback)

  Сомбинирует все элементы коллекции с применением определенной операции $callback

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $callback: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>`, :doc:`null </api_ru/.types/null>` 

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Конвертирует коллекцию в массив

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $withKeys: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: keys($collection)

  Возвращает все ключи коллекции

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: flatten($collection, $maxLevel = -1)

  Возвращает новый массив полученный исходя из всех элементов коллекции рекурсивно.

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $maxLevel: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`array </api_ru/.types/array>` 



.. include:: /api_ru.desc/php/lib/items.footer.rst

