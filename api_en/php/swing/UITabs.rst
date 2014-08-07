UITabs
----------------

.. include:: /api_en.desc/php/swing/UITabs.header.rst

.. php:class:: php\\swing\\UITabs

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 Class UITabs
 
 Events: change



**Properties**

----------

 .. php:attr:: selectedIndex

  :doc:`int </api_en/.types/int>`

 .. php:attr:: selectedComponent

  :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>`

 .. php:attr:: tabPlacement

  :doc:`php\\swing\\string - left, right, top, bottom </api_en/php/swing/string - left, right, top, bottom>`

 .. php:attr:: tabCount

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: addTab($title, $component, $icon = null)

  :param $title: :doc:`string </api_en/.types/string>` 
  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 
  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: getTitleAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setTitleAt($index, $value)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getToolTipTextAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setToolTipTextAt($index, $value)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $value: :doc:`string </api_en/.types/string>` 

 .. php:method:: getTabIconAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: setTabIconAt($index, $image)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $image: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: getTabComponentAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: setTabComponentAt($index, $component)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: removeTabAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 

 .. php:method:: removeAll()


 .. php:method:: indexAtPosition($x, $y)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: isEnabledAt($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setEnabledAt($index, $enabled)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $enabled: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/swing/UITabs.footer.rst

