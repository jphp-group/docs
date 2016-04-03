reflect
---------------

.. include:: /api_en.desc/php/lib/reflect.header.rst

.. php:class:: php\\lib\\reflect

 Class reflect



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: typeOf($object, $isLowerCase = false)

  :param $object: :doc:`object </api_en/.types/object>` 
  :param $isLowerCase: :doc:`bool </api_en/.types/bool>`  - (optional)
  :returns: :doc:`php\\lib\\false </api_en/php/lib/false>`, :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: typeModule($typeName)

  :param $typeName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\lang\\Module </api_en/php/lang/Module>`, :doc:`null </api_en/.types/null>` 

 .. php:staticmethod:: functionModule($funcName)

  :param $funcName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\lang\\Module </api_en/php/lang/Module>`, :doc:`null </api_en/.types/null>` 

 .. php:staticmethod:: newInstance($className, $args = null, $withConstruct = true)

  :param $className: :doc:`string </api_en/.types/string>` 
  :param $args: :doc:`array </api_en/.types/array>` 
  :param $withConstruct: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`object </api_en/.types/object>` 



.. include:: /api_en.desc/php/lib/reflect.footer.rst

