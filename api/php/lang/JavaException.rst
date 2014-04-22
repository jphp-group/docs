JavaException
----------------------

.. php:class:: php\\lang\\JavaException

 **extends**: :doc:`Exception </api/Exception>`


 Class JavaException

 .. php:method:: isRuntimeException()


  Check exception instance of java.lang.RuntimeException

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isNullPointerException()


  Check exception instance of java.lang.NullPointerException

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isIllegalArgumentException()


  Check exception instance of java.lang.IllegalArgumentException

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: isNumberFormatException()


  Check exception instance of java.lang.NumberFormatException

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: getExceptionClass()

  :returns: :doc:`php\\lang\\JavaClass </api/php/lang/JavaClass>` 

 .. php:method:: getJavaException()

  :returns: :doc:`php\\lang\\JavaObject </api/php/lang/JavaObject>` 

 .. php:method:: printJVMStackTrace()


