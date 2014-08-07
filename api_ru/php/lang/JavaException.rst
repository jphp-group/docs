JavaException
----------------------

.. include:: /api_ru.desc/php/lang/JavaException.header.rst

.. php:class:: php\\lang\\JavaException

 **extends**: :doc:`Exception </api_ru/Exception>`

**Children**

----------------------

 * **class** :doc:`php\\concurrent\\TimeoutException </api_ru/php/concurrent/TimeoutException>`
 * **class** :doc:`php\\io\\IOException </api_ru/php/io/IOException>`
 * **class** :doc:`php\\lang\\IllegalArgumentException </api_ru/php/lang/IllegalArgumentException>`
 * **class** :doc:`php\\lang\\IllegalStateException </api_ru/php/lang/IllegalStateException>`
 * **class** :doc:`php\\lang\\InterruptedException </api_ru/php/lang/InterruptedException>`
 * **class** :doc:`php\\lang\\NumberFormatException </api_ru/php/lang/NumberFormatException>`
 * **class** :doc:`php\\net\\SocketException </api_ru/php/net/SocketException>`
 * **class** :doc:`php\\util\\RegexException </api_ru/php/util/RegexException>`

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

