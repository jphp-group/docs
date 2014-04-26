Environment
--------------------

.. include:: /api_ru.desc/php/lang/Environment.header.rst

.. php:class:: php\\lang\\Environment

 Class Environment



**Constants**

----------

 .. php:const:: CONCURRENT

 .. php:const:: HOT_RELOAD



**Methods**

----------

 .. php:method:: __construct($parent = NULL, $flags = 0)

  :param $parent: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 
  :param $flags: :doc:`int </api_ru/.types/int>`  - Environment::HOT_RELOAD, Environment::CONCURRENT

 .. php:method:: execute($runnable)

  Выполняет $runnable в текущем своем окружении

  :param $runnable: :doc:`callable </api_ru/.types/callable>`  - - in new environment
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: importClass($className)

  Импортирует класс в свое окружение

  **throws** :doc:`php\\lang\\\\Exception </api_ru/php/lang//Exception>` - if class not found or already registered

  :param $className: :doc:`string </api_ru/.types/string>` 

 .. php:method:: exportClass($className)

  Экмпортирует класс из своего окружения

  **throws** :doc:`php\\lang\\\\Exception </api_ru/php/lang//Exception>` - if class not found or already registered

  :param $className: :doc:`string </api_ru/.types/string>` 

 .. php:method:: importFunction($functionName)

  Импортирует функцию в свое окружение

  **throws** :doc:`php\\lang\\\\Exception </api_ru/php/lang//Exception>` если функция не найдена или уже объявлена

  :param $functionName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: exportFunction($functionName)

  Экспортирует функцию из своего окружения

  **throws** :doc:`php\\lang\\\\Exception </api_ru/php/lang//Exception>` если функция не найдена или уже объявлена

  :param $functionName: :doc:`string </api_ru/.types/string>` 

 .. php:method:: defineConstant($name, $value, $caseSensitive = true)

  **throws** :doc:`php\\lang\\\\Exception </api_ru/php/lang//Exception>` - if constant already registered or value is not scalar type

  :param $name: :doc:`string </api_ru/.types/string>` 
  :param $value: :doc:`mixed </api_ru/.types/mixed>`  - - scalar value
  :param $caseSensitive: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: onMessage($callback)

  Обрабатывает сообщения, что были посланы в окружение

  :param $callback: :doc:`callable </api_ru/.types/callable>` 

 .. php:method:: sendMessage($message)

  Послать сообщение окружению

  :param $message: :doc:`mixed </api_ru/.types/mixed>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:staticmethod:: current()

  Взять окружение текущего выполнения

  :returns: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 



.. include:: /api_ru.desc/php/lang/Environment.footer.rst

