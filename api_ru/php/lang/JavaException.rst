JavaException
----------------------

.. include:: /api_ru.desc/php/lang/JavaException.header.rst

.. php:class:: php\\lang\\JavaException

 **extends**: :doc:`Exception </api_ru/Exception>`

**Children**

----------------------

 * **class** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`
 * **class** :doc:`php\\net\\SocketException </api_ru/php/net/SocketException>`

 Class JavaException



**Methods**

----------

 .. php:method:: isRuntimeException()

  Check exception instance of java.lang.RuntimeException

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isNullPointerException()

  Check exception instance of java.lang.NullPointerException

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isIllegalArgumentException()

  Check exception instance of java.lang.IllegalArgumentException

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isNumberFormatException()

  Check exception instance of java.lang.NumberFormatException

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getExceptionClass()

  :returns: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>` 

 .. php:method:: getJavaException()

  :returns: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 

 .. php:method:: printJVMStackTrace()




.. include:: /api_ru.desc/php/lang/JavaException.footer.rst

