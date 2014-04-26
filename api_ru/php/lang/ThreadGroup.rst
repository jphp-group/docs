ThreadGroup
--------------------

.. include:: /api_ru.desc/php/lang/ThreadGroup.header.rst

.. php:class:: php\\lang\\ThreadGroup

 Class ThreadGroup



**Methods**

----------

 .. php:method:: __construct($name, $parent = null)

  :param $name: 
  :param $parent: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getParent()

  :returns: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>`, :doc:`null </api_ru/.types/null>` 

 .. php:method:: getActiveCount()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getActiveGroupCount()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: isDaemon()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: setDaemon($value)

  :param $value: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: isDestroyed()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: getMaxPriority()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: setMaxPriority($value)

  :param $value: :doc:`int </api_ru/.types/int>` 

 .. php:method:: destroy()


 .. php:method:: checkAccess()

  Determines if the currently running thread has permission to
  modify this thread group.

  **throws** :doc:`php\\lang\\JavaException </api_ru/php/lang/JavaException>`


 .. php:method:: interrupt()




.. include:: /api_ru.desc/php/lang/ThreadGroup.footer.rst

