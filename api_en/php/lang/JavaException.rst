JavaException
----------------------

.. include:: /api_en.desc/php/lang/JavaException.header.rst

.. php:class:: php\\lang\\JavaException

 **extends**: :doc:`Exception </api_en/Exception>`

**Children**

----------------------

 * **class** :doc:`php\\concurrent\\TimeoutException </api_en/php/concurrent/TimeoutException>`
 * **class** :doc:`php\\io\\IOException </api_en/php/io/IOException>`
 * **class** :doc:`php\\lang\\IllegalArgumentException </api_en/php/lang/IllegalArgumentException>`
 * **class** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`
 * **class** :doc:`php\\lang\\InterruptedException </api_en/php/lang/InterruptedException>`
 * **class** :doc:`php\\lang\\NumberFormatException </api_en/php/lang/NumberFormatException>`
 * **class** :doc:`php\\net\\SocketException </api_en/php/net/SocketException>`
 * **class** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`
 * **class** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

 Class JavaException



**Methods**

----------

 .. php:method:: isRuntimeException()

  Check exception instance of java.lang.RuntimeException

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isNullPointerException()

  Check exception instance of java.lang.NullPointerException

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isIllegalArgumentException()

  Check exception instance of java.lang.IllegalArgumentException

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isNumberFormatException()

  Check exception instance of java.lang.NumberFormatException

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getExceptionClass()

  :returns: :doc:`php\\lang\\JavaClass </api_en/php/lang/JavaClass>` 

 .. php:method:: getJavaException()

  :returns: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>` 

 .. php:method:: printJVMStackTrace()




.. include:: /api_en.desc/php/lang/JavaException.footer.rst

