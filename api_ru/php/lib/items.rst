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

 .. php:staticmethod:: toArray($collection, $withKeys = false)

  Конвертирует коллекцию в массив

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $withKeys: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: toList($collection)

  Example: items::toList(['x' => 10, 20], 30, ['x' => 50, 60]) -> [10, 20, 30, 50, 60]

  :param $collection: 
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

 .. php:staticmethod:: sort($collection, $comparator = null, $saveKeys = false)

  Sorts the specified list into ascending order

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $comparator: :doc:`callable </api_ru/.types/callable>`  - ($o1, $o2) -> int where -1 smaller, 0 equal, 1 greater
  :param $saveKeys: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:staticmethod:: sortByKeys($collection, $comparator = null, $saveKeys = false)

  Sorts the specified list into ascending order by keys

  :param $collection: :doc:`array </api_ru/.types/array>`, :doc:`Iterator </api_ru/Iterator>` 
  :param $comparator: :doc:`callable </api_ru/.types/callable>`  - ($key1, $key2)
  :param $saveKeys: :doc:`bool </api_ru/.types/bool>` 
  :returns: :doc:`array </api_ru/.types/array>` 



.. include:: /api_ru.desc/php/lib/items.footer.rst

