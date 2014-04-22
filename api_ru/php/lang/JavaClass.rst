JavaClass
------------------

.. php:class:: php\\lang\\JavaClass

 **final** class


 .. php:method:: __construct($className)

  :param $className: :doc:`string </api_ru/.types/string>` - full name of java class

 .. php:method:: isStatic()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isFinal()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isAbstract()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isInterface()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isEnum()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isAnnotation()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isArray()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isPrimitive()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isAnonymousClass()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isMemberClass()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getSimpleName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getCanonicalName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getSuperClass()

  :returns: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>`, :doc:`null </api_ru/.types/null>` 

 .. php:method:: getModifiers()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isAnnotationPresent($annotationClassName)

  :param $annotationClassName: 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getInterfaces()

  :returns: :doc:`php\\lang\\JavaClass[] </api_ru/php/lang/JavaClass>` 

 .. php:method:: getDeclaredMethod($name, $types)

  :param $name: 
  :param $types: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`php\\lang\\JavaMethod </api_ru/php/lang/JavaMethod>` 

 .. php:method:: getDeclaredMethods()

  :returns: :doc:`php\\lang\\JavaMethod[] </api_ru/php/lang/JavaMethod>` 

 .. php:method:: getDeclaredField($name)

  :param $name: 
  :returns: :doc:`php\\lang\\JavaField </api_ru/php/lang/JavaField>` 

 .. php:method:: getDeclaredFields()

  :returns: :doc:`php\\lang\\JavaField[] </api_ru/php/lang/JavaField>` 

 .. php:method:: newInstance()

  :returns: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 

 .. php:method:: newInstanceArgs($types, $arguments)

  :param $types: :doc:`array </api_ru/.types/array>` 
  :param $arguments: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`php\\lang\\JavaObject </api_ru/php/lang/JavaObject>` 

 .. php:method:: isAssignableFrom($class)

  :param $class: :doc:`php\\lang\\JavaClass </api_ru/php/lang/JavaClass>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isSubClass($className)

  :param $className: 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getEnumConstants()

  :returns: :doc:`php\\lang\\JavaObject[] </api_ru/php/lang/JavaObject>` 

 .. php:method:: getResource($name)

  :param $name: 
  :returns: :doc:`string </api_ru/.types/string>`, :doc:`null </api_ru/.types/null>` - filename

 .. php:staticmethod:: primitive($name)

  :param $name: :doc:`string </api_ru/.types/string>` - [int, byte, short, char, float, double, boolean, long]

