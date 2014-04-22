Invoker
----------------

.. php:class:: php\\lang\\Invoker

 Класс для вызова методов/функций/и т.д.

 .. php:method:: __construct($callback)

  :param $callback: :doc:`callable </api_ru/callable>` 

 .. php:method:: callArray($args)

  Вызвать с массивом аргументов

  :param $args: :doc:`array </api_ru/array>` 
  :returns: :doc:`mixed </api_ru/mixed>` 

 .. php:method:: call()

  Вызвать текущий callback

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: __invoke()


 .. php:method:: canAccess()

  Проверить - есть ли доступ для вызова метода в какой-то момент

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: getDescription()

  Возвращает описание метода - название + информацию об аргументах

  :returns: :doc:`string </api_ru/string>` 

 .. php:method:: getArgumentCount()

  Возвращает количество аргументов текущего метода

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: isClosure()

  Проверяет - является ли метод замыканием

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isNamedFunction()

  Проверяет - является ли это именованной функцией

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isStaticCall()

  Проверяет - является ли это статичным вызовом

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isDynamicCall()

  Проверяет - является ли это динамичным вызовом

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:staticmethod:: of($callback)

  :param $callback: 
  :returns: :doc:`php\\lang\\Invoker </api_ru/php/lang/Invoker>`, :doc:`null </api_ru/null>` возвращает ``null`` если передан не валидный $callback

