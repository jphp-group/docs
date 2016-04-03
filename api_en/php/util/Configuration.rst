Configuration
----------------------

.. include:: /api_en.desc/php/util/Configuration.header.rst

.. php:class:: php\\util\\Configuration

 Class Configuration



**Methods**

----------

 .. php:method:: __construct($source = null, $encoding = 'UTF-8')

  :param $source: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $encoding: :doc:`string </api_en/.types/string>` 

 .. php:method:: has($key)

  :param $key: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: get($key, $def = null)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $def: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getArray($key, $def = [)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $def: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`string[] </api_en/.types/string>` 

 .. php:method:: getBoolean($key, $def = false)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $def: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getNumber($key, $def = 0)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $def: :doc:`int </api_en/.types/int>`, :doc:`float </api_en/.types/float>` 
  :returns: :doc:`int </api_en/.types/int>`, :doc:`float </api_en/.types/float>` 

 .. php:method:: getInteger($key, $def = 0)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $def: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: set($key, $value)

  :param $key: :doc:`string </api_en/.types/string>` 
  :param $value: :doc:`string </api_en/.types/string>`, :doc:`array </api_en/.types/array>` 
  :returns: :doc:`string </api_en/.types/string>` old value

 .. php:method:: put($values)

  :param $values: :doc:`array </api_en/.types/array>`, :doc:`Traversable </api_en/Traversable>` 

 .. php:method:: clear()


 .. php:method:: load($in, $encoding = 'UTF-8')

  :param $in: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $encoding: :doc:`string </api_en/.types/string>` 

 .. php:method:: save($out, $encoding = 'UTF-8')

  :param $out: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $encoding: :doc:`string </api_en/.types/string>` 

 .. php:method:: toArray()

  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/util/Configuration.footer.rst

