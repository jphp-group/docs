Module
---------------

.. include:: /api_ru.desc/php/lang/Module.header.rst

.. php:class:: php\\lang\\Module

 Class Module



**Methods**

----------

 .. php:method:: __construct($source, $compiled = false, $debugInformation = true)

  Register all functions and classes of module in current environment

  :param $source: :doc:`php\\io\\File </api_ru/php/io/File>`, :doc:`php\\io\\Stream </api_ru/php/io/Stream>`, :doc:`string </api_ru/.types/string>` 
  :param $compiled: :doc:`bool </api_ru/.types/bool>` 
  :param $debugInformation: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: call($variables = null)

  Include module and return result

  :param $variables: :doc:`array </api_ru/.types/array>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: dump($target, $saveDebugInfo = true)

  **throws** :doc:`>`

  :param $target: :doc:`php\\io\\File </api_ru/php/io/File>`, :doc:`php\\io\\Stream </api_ru/php/io/Stream>`, :doc:`string </api_ru/.types/string>` 
  :param $saveDebugInfo: :doc:`bool </api_ru/.types/bool>` 



.. include:: /api_ru.desc/php/lang/Module.footer.rst

