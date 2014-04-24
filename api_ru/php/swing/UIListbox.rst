UIListbox
-------------------

.. include:: /api_ru.desc/php/swing/UIListbox.header.rst

.. php:class:: php\\swing\\UIListbox

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`


 Class UIListbox



**Properties**

----------

 .. php:attr:: multiple

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: selectedIndex

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: selectedIndexes

  :doc:`int[] </api_ru/.types/int>`

 .. php:attr:: maxSelectionIndex

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: minSelectionIndex

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: visibleRowCount

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: selectionBackground

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: selectionForeground

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: horScrollPolicy

  :doc:`php\\swing\\string - ALWAYS, HIDDEN, AUTO </api_ru/php/swing/string - ALWAYS, HIDDEN, AUTO>`

 .. php:attr:: verScrollPolicy

  :doc:`php\\swing\\string - ALWAYS, HIDDEN, AUTO </api_ru/php/swing/string - ALWAYS, HIDDEN, AUTO>`



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




.. include:: /api_ru.desc/php/swing/UIListbox.footer.rst

