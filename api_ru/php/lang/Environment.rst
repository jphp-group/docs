Environment
--------------------

.. include:: /api_ru.desc/php/lang/Environment.header.rst

.. php:class:: php\\lang\\Environment

 Class Environment



**Methods**

----------

 .. php:method:: __construct($parent = NULL, $flags = 0)

  :param $parent: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 
  :param $flags: :doc:`int </api_ru/.types/int>` Environment::HOT_RELOAD, Environment::CONCURRENT

 .. php:method:: execute($runnable)

  Выполняет $runnable в текущем своем окружении

  :param $runnable: :doc:`callable </api_ru/.types/callable>` - in new environment
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: importClass($className)

  Импортирует класс в свое окружение

  :param $className: 

 .. php:method:: exportClass($className)

  Экмпортирует класс из своего окружения

  :param $className: 

 .. php:method:: importFunction($functionName)

  Импортирует функцию в свое окружение

  :param $functionName: 

 .. php:method:: exportFunction($functionName)

  Экспортирует функцию из своего окружения

  :param $functionName: 

 .. php:method:: defineConstant($name, $value, $caseSensitive = true)

  :param $name: 
  :param $value: :doc:`mixed </api_ru/.types/mixed>` - scalar value
  :param $caseSensitive: 

 .. php:method:: onMessage($callback)

  Обрабатывает сообщения, что были посланы в окружение

  :param $callback: :doc:`callable </api_ru/.types/callable>` 

 .. php:method:: sendMessage($message)

  Послать сообщение окружению

  :param $message: 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:staticmethod:: current()

  Взять окружение текущего выполнения

  :returns: :doc:`php\\lang\\Environment </api_ru/php/lang/Environment>` 



.. include:: /api_ru.desc/php/lang/Environment.footer.rst

