Environment
--------------------

.. php:class:: php\\lang\\Environment

 Class Environment

 .. php:method:: __construct($parent = NULL, $flags = 0)

  :param $parent: :doc:`php\\lang\\Environment </api/php/lang/Environment>` 
  :param $flags: :doc:`int </api/int>` - HOT_RELOAD, CONCURRENT

 .. php:method:: execute($runnable)

  :param $runnable: :doc:`callable </api/callable>` - in new environment
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: importClass($className)

  :param $className: 

 .. php:method:: exportClass($className)

  :param $className: 

 .. php:method:: importFunction($functionName)

  :param $functionName: 

 .. php:method:: exportFunction($functionName)

  :param $functionName: 

 .. php:method:: defineConstant($name, $value, $caseSensitive = true)

  :param $name: 
  :param $value: :doc:`mixed </api/mixed>` - scalar value
  :param $caseSensitive: 

 .. php:method:: onMessage($callback)

  :param $callback: :doc:`callable </api/callable>` 

 .. php:method:: sendMessage($message)

  :param $message: 
  :returns: :doc:`mixed </api/mixed>` 

 .. php:staticmethod:: current()


  Get environment of current execution

  :returns: :doc:`php\\lang\\Environment </api/php/lang/Environment>` 

