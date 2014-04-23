UIContainer
---------------------

.. include:: /api_ru.desc/php/swing/UIContainer.header.rst

.. php:class:: php\\swing\\UIContainer

 **abstract** class

 **extends**: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>`




**Methods**

----------

 .. php:method:: add($component, $index = null)

  Add child component

  :param $component: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 
  :param $index: 

 .. php:method:: remove($component)

  :param $component: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 

 .. php:method:: removeByIndex($index)

  :param $index: 

 .. php:method:: removeAll()


 .. php:method:: getComponentCount()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getComponent($index)

  :param $index: 
  :returns: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 

 .. php:method:: getComponentByGroup($group)

  Find first component by group

  :param $group: 
  :returns: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>`, :doc:`NULL </api_ru/.types/NULL>` 

 .. php:method:: getComponentsByGroup($group)

  Find all components in group

  :param $group: 
  :returns: :doc:`php\\swing\\UIElement[] </api_ru/php/swing/UIElement>` 



.. include:: /api_ru.desc/php/swing/UIContainer.footer.rst

