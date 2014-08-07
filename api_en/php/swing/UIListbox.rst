UIListbox
-------------------

.. include:: /api_en.desc/php/swing/UIListbox.header.rst

.. php:class:: php\\swing\\UIListbox

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 Class UIListbox



**Properties**

----------

 .. php:attr:: multiple

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: selectedIndex

  :doc:`int </api_en/.types/int>`

 .. php:attr:: selectedIndexes

  :doc:`int[] </api_en/.types/int>`

 .. php:attr:: maxSelectionIndex

  :doc:`int </api_en/.types/int>`

 .. php:attr:: minSelectionIndex

  :doc:`int </api_en/.types/int>`

 .. php:attr:: visibleRowCount

  :doc:`int </api_en/.types/int>`

 .. php:attr:: selectionBackground

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: selectionForeground

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: horScrollPolicy

  :doc:`php\\swing\\string - ALWAYS, HIDDEN, AUTO </api_en/php/swing/string - ALWAYS, HIDDEN, AUTO>`

 .. php:attr:: verScrollPolicy

  :doc:`php\\swing\\string - ALWAYS, HIDDEN, AUTO </api_en/php/swing/string - ALWAYS, HIDDEN, AUTO>`

 .. php:attr:: itemCount

  :doc:`int </api_en/.types/int>`

  **read-only**




**Methods**

----------

 .. php:method:: setItems($items)

  :param $items: :doc:`array </api_en/.types/array>` 

 .. php:method:: getItem($index)

  :param $index: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>` 

 .. php:method:: addItem($item)

  :param $item: :doc:`string </api_en/.types/string>` 

 .. php:method:: insertItem($index, $item)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $item: :doc:`string </api_en/.types/string>` 

 .. php:method:: removeItem($index)

  :param $index: :doc:`int </api_en/.types/int>` 

 .. php:method:: removeAllItems()


 .. php:method:: onCellRender($callback = null)

  :param $callback: :doc:`callable </api_en/.types/callable>`  - (UIListbox $self, UILabel $template, $value, int $index, bool isSelected, bool cellHasFocus)



.. include:: /api_en.desc/php/swing/UIListbox.footer.rst

