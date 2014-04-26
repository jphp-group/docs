Environment
--------------------

.. include:: /api_en.desc/php/lang/Environment.header.rst

.. php:class:: php\\lang\\Environment

 Class Environment



**Constants**

----------

 .. php:const:: CONCURRENT

 .. php:const:: HOT_RELOAD



**Methods**

----------

 .. php:method:: __construct($parent = NULL, $flags = 0)

  :param $parent: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 
  :param $flags: :doc:`int </api_en/.types/int>`  - Environment::HOT_RELOAD, Environment::CONCURRENT

 .. php:method:: execute($runnable)

  Executes $runnable in the environment

  :param $runnable: :doc:`callable </api_en/.types/callable>`  - - in new environment
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: importClass($className)

  Imports the $className to the environment

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>` - if class not found or already registered

  :param $className: :doc:`string </api_en/.types/string>` 

 .. php:method:: exportClass($className)

  Exports the $className from th environment

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>` - if class not found or already registered

  :param $className: :doc:`string </api_en/.types/string>` 

 .. php:method:: importFunction($functionName)

  Imports the $functionName to the environment

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>` - if function not found or already registered

  :param $functionName: :doc:`string </api_en/.types/string>` 

 .. php:method:: exportFunction($functionName)

  Exports the $functionName from the environment

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>` - if function not found or already registered

  :param $functionName: :doc:`string </api_en/.types/string>` 

 .. php:method:: defineConstant($name, $value, $caseSensitive = true)

  **throws** :doc:`php\\lang\\\\Exception </api_en/php/lang//Exception>` - if constant already registered or value is not scalar type

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`mixed </api_en/.types/mixed>`  - - scalar value
  :param $caseSensitive: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: onMessage($callback)

  Handles messages that sent to the environment

  :param $callback: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: sendMessage($message)

  Send message to the environment

  :param $message: :doc:`mixed </api_en/.types/mixed>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:staticmethod:: current()

  Get environment of current execution

  :returns: :doc:`php\\lang\\Environment </api_en/php/lang/Environment>` 



.. include:: /api_en.desc/php/lang/Environment.footer.rst

