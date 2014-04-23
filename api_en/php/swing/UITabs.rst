UITabs
----------------

.. include:: /api_en.desc/php/swing/UITabs.header.rst

.. php:class:: php\\swing\\UITabs

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 Class UITabs



**Properties**

----------

 .. php:attr:: selectedIndex

  :doc:`int </api_en/.types/int>`

 .. php:attr:: selectedComponent

  :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>`

 .. php:attr:: tabPlacement

  :doc:`php\\swing\\string - left, right, top, bottom </api_en/php/swing/string - left, right, top, bottom>`



**Methods**

----------

 .. php:method:: addTab($title, $component, $icon = null)

  :param $title: 
  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 
  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: getTitleAt($index)

  :param $index: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setTitleAt($index, $value)

  :param $index: 
  :param $value: 

 .. php:method:: getToolTipTextAt($index)

  :param $index: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setToolTipTextAt($index, $value)

  :param $index: 
  :param $value: 

 .. php:method:: getTabIconAt($index)

  :param $index: 
  :returns: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: setTabIconAt($index, $image)

  :param $index: 
  :param $image: :doc:`php\\swing\\Image </api_en/php/swing/Image>` 

 .. php:method:: getTabComponentAt($index)

  :param $index: 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: setTabComponentAt($index, $component)

  :param $index: 
  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: removeTabAt($index)

  :param $index: 

 .. php:method:: removeAll()


 .. php:method:: indexAtPosition($x, $y)

  :param $x: 
  :param $y: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: isEnabledAt($index)

  :param $index: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setEnabledAt($index, $enabled)

  :param $index: 
  :param $enabled: 



.. include:: /api_en.desc/php/swing/UITabs.footer.rst

