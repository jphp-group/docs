Invoker
----------------

.. php:class:: php\\lang\\Invoker

 Class for calling methods/functions/etc.

 .. php:method:: __construct($callback)

  :param $callback: :doc:`callable </api_en/callable>` 

 .. php:method:: callArray($args)

  Call with array arguments

  :param $args: :doc:`array </api_en/array>` 
  :returns: :doc:`mixed </api_en/mixed>` 

 .. php:method:: call()

  Call the current callback

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: __invoke()


 .. php:method:: canAccess()

  Check access to invoke the method at a moment

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: getDescription()

  Returns description of the method - name + argument info

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getArgumentCount()

  Returns argument count of the method

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: isClosure()

  Checks it is a closure

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isNamedFunction()

  Checks it is a named function

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isStaticCall()

  Checks it is a static call

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: isDynamicCall()

  Checks it is a dynamic call

  :returns: :doc:`bool </api_en/bool>` 

 .. php:staticmethod:: of($callback)

  :param $callback: 
  :returns: :doc:`php\\lang\\Invoker </api_en/php/lang/Invoker>`, :doc:`null </api_en/null>` - returns ``null`` if passed is not callable

