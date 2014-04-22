Environment
--------------------

.. php:class:: php\\lang\\Environment

 Class Environment

 .. php:method:: __construct($parent = NULL, $flags = 0)

  :param $parent: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :param $flags: :doc:`int </api_en/.types/int>` Environment::HOT_RELOAD, Environment::CONCURRENT

 .. php:method:: execute($runnable)

  Executes $runnable in the environment

  :param $runnable: :doc:`callable </api_en/.types/callable>` - in new environment
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: importClass($className)

  Imports the $className to the environment

  :param $className: 

 .. php:method:: exportClass($className)

  Exports the $className from th environment

  :param $className: 

 .. php:method:: importFunction($functionName)

  Imports the $functionName to the environment

  :param $functionName: 

 .. php:method:: exportFunction($functionName)

  Exports the $functionName from the environment

  :param $functionName: 

 .. php:method:: defineConstant($name, $value, $caseSensitive = true)

  :param $name: 
  :param $value: :doc:`mixed </api_en/.types/mixed>` - scalar value
  :param $caseSensitive: 

 .. php:method:: onMessage($callback)

  Handles messages that sent to the environment

  :param $callback: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: sendMessage($message)

  Send message to the environment

  :param $message: 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: current()

  Get environment of current execution

  :returns: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 

