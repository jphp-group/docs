GettersSetters
-----------------------

.. include:: /api_en.desc/php/lang/GettersSetters.header.rst

.. php:class:: php\\lang\\GettersSetters

 To implement a property with a setter and getter, define the following methods::
 
 protected __set[prop_name]($value) // for setter (or not if you want to implement a read-only property)
 protected __get[prop_name]() // for getter
 
 Class Properties



**Methods**

----------

 .. php:method:: __set($name, $value)

  :param $name: 
  :param $value: 

 .. php:method:: __get($name)

  :param $name: 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: __isset($name)

  :param $name: 

 .. php:method:: __unset($name)

  :param $name: 



.. include:: /api_en.desc/php/lang/GettersSetters.footer.rst

