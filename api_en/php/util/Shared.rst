Shared
---------------

.. include:: /api_en.desc/php/util/Shared.header.rst

.. php:class:: php\\util\\Shared

 Class to work with shared memory of Environments
 
 Class Shared



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: value($name, $creator = null)

  Get or create if does not exist and get a shared value

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $creator: :doc:`callable </api_en/.types/callable>`  - returns init value
  :returns: :doc:`php\\util\\SharedValue </api_en/php/util/SharedValue>` 

 .. php:staticmethod:: reset($name)

  Removes the value by $name.

  :param $name: :doc:`php\\util\\String </api_en/php/util/String>` 
  :returns: :doc:`php\\util\\SharedValue </api_en/php/util/SharedValue>` removed value

 .. php:staticmethod:: resetAll()




.. include:: /api_en.desc/php/util/Shared.footer.rst

