Invoker
----------------

.. include:: /api_ru.desc/php/lang/Invoker.header.rst

.. php:class:: php\\lang\\Invoker

 Класс для вызова методов/функций/и т.д.



**Methods**

----------

 .. php:method:: __construct($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` 

 .. php:method:: callArray($args)

  Вызвать с массивом аргументов

  :param $args: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: call()

  Вызвать текущий callback

  :returns: :doc:`int </api_ru/.types/int>`, :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: __invoke()


 .. php:method:: canAccess()

  Проверить - есть ли доступ для вызова метода в какой-то момент

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getDescription()

  Возвращает описание метода - название + информацию об аргументах

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getArgumentCount()

  Возвращает количество аргументов текущего метода

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isClosure()

  Проверяет - является ли метод замыканием

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isNamedFunction()

  Проверяет - является ли это именованной функцией

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isStaticCall()

  Проверяет - является ли это статичным вызовом

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isDynamicCall()

  Проверяет - является ли это динамичным вызовом

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: of($callback)

  :param $callback: :doc:`mixed </api_ru/.types/mixed>`, :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`php\\lang\\Invoker </api_ru/php/lang/Invoker>`, :doc:`null </api_ru/.types/null>` возвращает ``null`` если передан не валидный $callback



.. include:: /api_ru.desc/php/lang/Invoker.footer.rst

