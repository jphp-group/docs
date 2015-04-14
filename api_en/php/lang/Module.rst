Module
---------------

.. include:: /api_en.desc/php/lang/Module.header.rst

.. php:class:: php\\lang\\Module

 Class Module



**Methods**

----------

 .. php:method:: __construct($source, $compiled = false, $debugInformation = true)

  Register all functions and classes of module in current environment

  :param $source: :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`string </api_en/.types/string>` 
  :param $compiled: :doc:`bool </api_en/.types/bool>` 
  :param $debugInformation: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: call($variables = null)

  Include module and return result

  :param $variables: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: dump($target, $saveDebugInfo = true)

  **throws** :doc:`>`

  :param $target: :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`string </api_en/.types/string>` 
  :param $saveDebugInfo: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/lang/Module.footer.rst

