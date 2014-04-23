Invoker
----------------

.. include:: /api_en.desc/php/lang/Invoker.header.rst

.. php:class:: php\\lang\\Invoker

 Class for calling methods/functions/etc.



**Methods**

----------

 .. php:method:: __construct($callback)

  :param $callback: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: callArray($args)

  Call with array arguments

  :param $args: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: call()

  Call the current callback

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: __invoke()


 .. php:method:: canAccess()

  Check access to invoke the method at a moment

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDescription()

  Returns description of the method - name + argument info

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getArgumentCount()

  Returns argument count of the method

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: isClosure()

  Checks it is a closure

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isNamedFunction()

  Checks it is a named function

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isStaticCall()

  Checks it is a static call

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isDynamicCall()

  Checks it is a dynamic call

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: of($callback)

  :param $callback: 
  :returns: :doc:`php\\lang\\Invoker </api_en/php/lang/Invoker>`, :doc:`null </api_en/.types/null>` - returns ``null`` if passed is not callable



.. include:: /api_en.desc/php/lang/Invoker.footer.rst

