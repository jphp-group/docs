JavaMethod
-------------------

.. php:class:: php\\lang\\JavaMethod

 **final** class

 **extends**: :doc:`php\\lang\\JavaReflection </api_ru/php/lang/JavaReflection>`
 .. php:method:: invoke($object = null)

  Invoke method

  :param $object: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 

 .. php:method:: invokeArgs($object = null, $arguments)

  :param $object: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 
  :param $arguments: :doc:`array </api_ru/array>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/string>` 

 .. php:method:: isStatic()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isFinal()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isAbstract()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isPublic()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isProtected()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isPrivate()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isNative()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isSynchronized()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isVarArgs()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: getDeclaringClass()

  :returns: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>` 

 .. php:method:: getReturnedType()

  :returns: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>` 

 .. php:method:: isAnnotationPresent($annotationClassName)

  :param $annotationClassName: 
  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: getParameterTypes()

  :returns: :doc:`php\\lang\\JavaClass[] </api_ru/php/lang/JavaClass>` 

 .. php:method:: getParameterCount()

  :returns: :doc:`int </api_ru/int>` 

