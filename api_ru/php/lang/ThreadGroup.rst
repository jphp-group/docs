ThreadGroup
--------------------

.. php:class:: php\\lang\\ThreadGroup

 Class ThreadGroup

 .. php:method:: __construct($name, $parent = null)

  :param $name: 
  :param $parent: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_ru/string>` 

 .. php:method:: getParent()

  :returns: :doc:`php\\lang\\ThreadGroup </api_ru/php/lang/ThreadGroup>`, :doc:`null </api_ru/null>` 

 .. php:method:: getActiveCount()

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: getActiveGroupCount()

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: isDaemon()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: setDaemon($value)

  :param $value: 

 .. php:method:: isDestroyed()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: getMaxPriority()

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: setMaxPriority($value)

  :param $value: 

 .. php:method:: destroy()


 .. php:method:: checkAccess()

  Determines if the currently running thread has permission to
  modify this thread group.


 .. php:method:: interrupt()


