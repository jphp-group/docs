ThreadGroup
--------------------

.. php:class:: php\\lang\\ThreadGroup

 Class ThreadGroup

 .. php:method:: __construct($name, $parent = null)

  :param $name: 
  :param $parent: :doc:`php\\lang\\ThreadGroup </api_en/php/lang/ThreadGroup>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/string>` 

 .. php:method:: getParent()

  :returns: :doc:`php\\lang\\ThreadGroup </api_en/php/lang/ThreadGroup>`, :doc:`null </api_en/null>` 

 .. php:method:: getActiveCount()

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: getActiveGroupCount()

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: isDaemon()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: setDaemon($value)

  :param $value: 

 .. php:method:: isDestroyed()

  :returns: :doc:`bool </api_en/bool>` 

 .. php:method:: getMaxPriority()

  :returns: :doc:`int </api_en/int>` 

 .. php:method:: setMaxPriority($value)

  :param $value: 

 .. php:method:: destroy()


 .. php:method:: checkAccess()

  Determines if the currently running thread has permission to
  modify this thread group.


 .. php:method:: interrupt()


