UIContainer
---------------------

.. include:: /api_ru.desc/php/swing/UIContainer.header.rst

.. php:class:: php\\swing\\UIContainer

 **abstract** class

 **extends**: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>`

**Children**

----------------------

 * **abstract** **class** :doc:`php\\swing\\UITextElement </api_ru/php/swing/UITextElement>`
 * **class** :doc:`php\\swing\\UIAbstractIButton </api_ru/php/swing/UIAbstractIButton>`
 * **class** :doc:`php\\swing\\UIColorChooser </api_ru/php/swing/UIColorChooser>`
 * **class** :doc:`php\\swing\\UICombobox </api_ru/php/swing/UICombobox>`
 * **class** :doc:`php\\swing\\UIDesktopPanel </api_ru/php/swing/UIDesktopPanel>`
 * **class** :doc:`php\\swing\\UIFileChooser </api_ru/php/swing/UIFileChooser>`
 * **class** :doc:`php\\swing\\UIImage </api_ru/php/swing/UIImage>`
 * **class** :doc:`php\\swing\\UIInternalForm </api_ru/php/swing/UIInternalForm>`
 * **class** :doc:`php\\swing\\UILabel </api_ru/php/swing/UILabel>`
 * **class** :doc:`php\\swing\\UIListbox </api_ru/php/swing/UIListbox>`
 * **class** :doc:`php\\swing\\UIMenuBar </api_ru/php/swing/UIMenuBar>`
 * **class** :doc:`php\\swing\\UIPanel </api_ru/php/swing/UIPanel>`
 * **class** :doc:`php\\swing\\UIPopupMenu </api_ru/php/swing/UIPopupMenu>`
 * **class** :doc:`php\\swing\\UIProgress </api_ru/php/swing/UIProgress>`
 * **class** :doc:`php\\swing\\UIScrollPanel </api_ru/php/swing/UIScrollPanel>`
 * **class** :doc:`php\\swing\\UISlider </api_ru/php/swing/UISlider>`
 * **class** :doc:`php\\swing\\UITable </api_ru/php/swing/UITable>`
 * **class** :doc:`php\\swing\\UITabs </api_ru/php/swing/UITabs>`
 * **class** :doc:`php\\swing\\UIToolBar </api_ru/php/swing/UIToolBar>`
 * **class** :doc:`php\\swing\\UITree </api_ru/php/swing/UITree>`
 * **class** :doc:`php\\swing\\UIUnknown </api_ru/php/swing/UIUnknown>`
 * **class** :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>`



**Methods**

----------

 .. php:method:: add($component, $index = null, $constraints = null)

  Add child component

  :param $component: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 
  :param $index: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 
  :param $constraints: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 

 .. php:method:: setLayout($type)

  :param $type: :doc:`string </api_ru/.types/string>`  - - absolute, grid, flow, grid-bag, border, card

 .. php:method:: remove($component)

  :param $component: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 

 .. php:method:: removeByIndex($index)

  **throws** :doc:`>`

  :param $index: :doc:`int </api_ru/.types/int>` 

 .. php:method:: removeAll()


 .. php:method:: getComponentCount()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getComponent($index)

  **throws** :doc:`>`

  :param $index: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 

 .. php:method:: getComponents()

  :returns: :doc:`php\\swing\\UIElement[] </api_ru/php/swing/UIElement>` 

 .. php:method:: getComponentByGroup($group)

  Find first component by group

  :param $group: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>`, :doc:`NULL </api_ru/.types/NULL>` 

 .. php:method:: getComponentsByGroup($group)

  Find all components in group

  :param $group: :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement[] </api_ru/php/swing/UIElement>` 



.. include:: /api_ru.desc/php/swing/UIContainer.footer.rst

