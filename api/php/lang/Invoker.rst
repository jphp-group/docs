Invoker
----------------

.. php:class:: php\\lang\\Invoker

 Class Invoker

 .. php:method:: __construct($callback)

  :param $callback: :doc:`callable </api/callable>` 

 .. php:method:: callArray($args)

  :param $args: :doc:`array </api/array>` 
  :returns: :doc:`mixed </api/mixed>` 

 .. php:method:: call()

  :returns: :doc:`int </api/int>` 

 .. php:method:: __invoke()


 .. php:method:: canAccess()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: getDescription()

  :returns: :doc:`string </api/string>` 

 .. php:method:: getArgumentCount()

  :returns: :doc:`int </api/int>` 

 .. php:method:: isClosure()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isNamedFunction()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isStaticCall()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isDynamicCall()

  :returns: :doc:`bool </api/bool>` 

 .. php:staticmethod:: of($callback)

  :param $callback: 
  :returns: :doc:`php\\lang\\Invoker </api/php/lang/Invoker>`, :doc:`null </api/null>` - returns null if passed is not callable

