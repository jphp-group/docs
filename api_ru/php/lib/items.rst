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

