JavaMethod
-------------------

.. include:: /api_en.desc/php/lang/JavaMethod.header.rst

.. php:class:: php\\lang\\JavaMethod

 **final** class

 **extends**: :doc:`php\\lang\\JavaReflection </api_en/php/lang/JavaReflection>`




**Methods**

----------

 .. php:method:: invoke($object = null)

  Invoke method

  :param $object: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>` 

 .. php:method:: invokeArgs($object = null, $arguments)

  :param $object: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>` 
  :param $arguments: :doc:`array </api_en/.types/array>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: isStatic()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isFinal()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAbstract()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isPublic()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isProtected()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isPrivate()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isNative()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isSynchronized()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isVarArgs()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getDeclaringClass()

  :returns: :doc:`php\\lang\\JavaClass </api_en/php/lang/JavaClass>` 

 .. php:method:: getReturnedType()

  :returns: :doc:`php\\lang\\JavaClass </api_en/php/lang/JavaClass>` 

 .. php:method:: isAnnotationPresent($annotationClassName)

  :param $annotationClassName: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getParameterTypes()

  :returns: :doc:`php\\lang\\JavaClass[] </api_en/php/lang/JavaClass>` 

 .. php:method:: getParameterCount()

  :returns: :doc:`int </api_en/.types/int>` 



.. include:: /api_en.desc/php/lang/JavaMethod.footer.rst

