UICombobox
--------------------

.. include:: /api_ru.desc/php/swing/UICombobox.header.rst

.. php:class:: php\\swing\\UICombobox

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`




**Properties**

----------

 .. php:attr:: readOnly

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: popupVisible

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: lightweightPopup

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: itemCount

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: selectedIndex

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: maxRowCount

  :doc:`int </api_ru/.types/int>`



**Methods**

----------

 .. php:method:: setItems($items)

  :param $items: :doc:`array </api_ru/.types/array>` 

 .. php:method:: getItem($index)

  :param $index: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`string </api_ru/.types/string>`, :doc:`null </api_ru/.types/null>` 

 .. php:method:: addItem($item)

  :param $item: :doc:`string </api_ru/.types/string>` 

 .. php:method:: insertItem($index, $item)

  :param $index: :doc:`int </api_ru/.types/int>` 
  :param $item: :doc:`string </api_ru/.types/string>` 

 .. php:method:: removeItem($index)

  :param $index: :doc:`int </api_ru/.types/int>` 

 .. php:method:: removeAllItems()


 .. php:method:: onCellRender($callback = null)

  :param $callback: :doc:`callable </api_ru/.types/callable>`  - (UICombobox $self, UILabel $template, $value, int $index, bool isSelected, bool cellHasFocus)



.. include:: /api_ru.desc/php/swing/UICombobox.footer.rst

