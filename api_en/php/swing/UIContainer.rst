UIContainer
---------------------

.. include:: /api_en.desc/php/swing/UIContainer.header.rst

.. php:class:: php\\swing\\UIContainer

 **abstract** class

 **extends**: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>`

**Children**

----------------------

 * **abstract** **class** :doc:`php\\swing\\UITextElement </api_en/php/swing/UITextElement>`
 * **class** :doc:`php\\swing\\UIAbstractIButton </api_en/php/swing/UIAbstractIButton>`
 * **class** :doc:`php\\swing\\UIColorChooser </api_en/php/swing/UIColorChooser>`
 * **class** :doc:`php\\swing\\UICombobox </api_en/php/swing/UICombobox>`
 * **class** :doc:`php\\swing\\UIFileChooser </api_en/php/swing/UIFileChooser>`
 * **class** :doc:`php\\swing\\UIImage </api_en/php/swing/UIImage>`
 * **class** :doc:`php\\swing\\UILabel </api_en/php/swing/UILabel>`
 * **class** :doc:`php\\swing\\UIListbox </api_en/php/swing/UIListbox>`
 * **class** :doc:`php\\swing\\UIMenuBar </api_en/php/swing/UIMenuBar>`
 * **class** :doc:`php\\swing\\UIPanel </api_en/php/swing/UIPanel>`
 * **class** :doc:`php\\swing\\UIPopupMenu </api_en/php/swing/UIPopupMenu>`
 * **class** :doc:`php\\swing\\UIProgress </api_en/php/swing/UIProgress>`
 * **class** :doc:`php\\swing\\UIScrollPanel </api_en/php/swing/UIScrollPanel>`
 * **class** :doc:`php\\swing\\UISlider </api_en/php/swing/UISlider>`
 * **class** :doc:`php\\swing\\UITable </api_en/php/swing/UITable>`
 * **class** :doc:`php\\swing\\UITabs </api_en/php/swing/UITabs>`
 * **class** :doc:`php\\swing\\UIToolBar </api_en/php/swing/UIToolBar>`
 * **class** :doc:`php\\swing\\UITree </api_en/php/swing/UITree>`
 * **class** :doc:`php\\swing\\UIUnknown </api_en/php/swing/UIUnknown>`
 * **class** :doc:`php\\swing\\UIWindow </api_en/php/swing/UIWindow>`



**Methods**

----------

 .. php:method:: add($component, $index = null)

  Add child component

  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 
  :param $index: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 

 .. php:method:: remove($component)

  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: removeByIndex($index)

  **throws** :doc:`>`

  :param $index: :doc:`int </api_en/.types/int>` 

 .. php:method:: removeAll()


 .. php:method:: getComponentCount()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getComponent($index)

  **throws** :doc:`>`

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: getComponentByGroup($group)

  Find first component by group

  :param $group: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>`, :doc:`NULL </api_en/.types/NULL>` 

 .. php:method:: getComponentsByGroup($group)

  Find all components in group

  :param $group: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement[] </api_en/php/swing/UIElement>` 



.. include:: /api_en.desc/php/swing/UIContainer.footer.rst

