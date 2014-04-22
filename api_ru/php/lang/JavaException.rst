JavaException
----------------------

.. php:class:: php\\lang\\JavaException

 **extends**: :doc:`Exception </api_ru/Exception>`


 Class JavaException

 .. php:method:: isRuntimeException()

  Check exception instance of java.lang.RuntimeException

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isNullPointerException()

  Check exception instance of java.lang.NullPointerException

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isIllegalArgumentException()

  Check exception instance of java.lang.IllegalArgumentException

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isNumberFormatException()

  Check exception instance of java.lang.NumberFormatException

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: getExceptionClass()

  :returns: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>` 

 .. php:method:: getJavaException()

  :returns: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 

 .. php:method:: printJVMStackTrace()


