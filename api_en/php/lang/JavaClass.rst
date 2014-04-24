JavaClass
------------------

.. include:: /api_en.desc/php/lang/JavaClass.header.rst

.. php:class:: php\\lang\\JavaClass

 **final** class




**Methods**

----------

 .. php:method:: __construct($className)

  :param $className: :doc:`string </api_en/.types/string>`  - - full name of java class

 .. php:method:: isStatic()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isFinal()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAbstract()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isInterface()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isEnum()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAnnotation()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isArray()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isPrimitive()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAnonymousClass()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isMemberClass()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getSimpleName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getCanonicalName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getSuperClass()

  :returns: :doc:`php\\lang\\JavaClass </api_en/php/lang/JavaClass>`, :doc:`null </api_en/.types/null>` 

 .. php:method:: getModifiers()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: isAnnotationPresent($annotationClassName)

  :param $annotationClassName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getInterfaces()

  :returns: :doc:`php\\lang\\JavaClass[] </api_en/php/lang/JavaClass>` 

 .. php:method:: getDeclaredMethod($name, $types)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $types: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\lang\\JavaMethod </api_en/php/lang/JavaMethod>` 

 .. php:method:: getDeclaredMethods()

  :returns: :doc:`php\\lang\\JavaMethod[] </api_en/php/lang/JavaMethod>` 

 .. php:method:: getDeclaredField($name)

  :param $name: 
  :returns: :doc:`php\\lang\\JavaField </api_en/php/lang/JavaField>` 

 .. php:method:: getDeclaredFields()

  :returns: :doc:`php\\lang\\JavaField[] </api_en/php/lang/JavaField>` 

 .. php:method:: newInstance()

  :returns: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>` 

 .. php:method:: newInstanceArgs($types, $arguments)

  :param $types: :doc:`array </api_en/.types/array>` 
  :param $arguments: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\lang\\JavaObject </api_en/php/lang/JavaObject>` 

 .. php:method:: isAssignableFrom($class)

  :param $class: :doc:`php\\lang\\JavaClass </api_en/php/lang/JavaClass>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isSubClass($className)

  :param $className: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getEnumConstants()

  :returns: :doc:`php\\lang\\JavaObject[] </api_en/php/lang/JavaObject>` 

 .. php:method:: getResource($name)

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>` - filename

 .. php:staticmethod:: primitive($name)

  :param $name: :doc:`string </api_en/.types/string>`  - - [int, byte, short, char, float, double, boolean, long]



.. include:: /api_en.desc/php/lang/JavaClass.footer.rst

