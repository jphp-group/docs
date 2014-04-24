UITable
-----------------

.. include:: /api_ru.desc/php/swing/UITable.header.rst

.. php:class:: php\\swing\\UITable

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`


 Class UITable



**Properties**

----------

 .. php:attr:: dragEnabled

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: selectionBackground

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: selectionForeground

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: gridColor

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: editingColumn

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: editingRow

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: rowMargin

  :doc:`int </api_ru/.types/int>`



**Methods**

----------

 .. php:method:: setRowHeight($height, $row = null)

  :param $height: :doc:`int </api_ru/.types/int>` 
  :param $row: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 

 .. php:method:: getRowHeight($row = null)

  :param $row: :doc:`null </api_ru/.types/null>`, :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: setValueAt($value, $row, $column)

  :param $value: :doc:`string </api_ru/.types/string>`, :doc:`null </api_ru/.types/null>` 
  :param $row: :doc:`int </api_ru/.types/int>` 
  :param $column: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getValueAt($row, $column)

  :param $row: :doc:`int </api_ru/.types/int>` 
  :param $column: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`string </api_ru/.types/string>`, :doc:`null </api_ru/.types/null>` 

 .. php:method:: columnAtPoint($x, $y)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: rowAtPoint($x, $y)

  :param $x: :doc:`int </api_ru/.types/int>` 
  :param $y: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: editCellAt($row, $column)

  :param $row: :doc:`int </api_ru/.types/int>` 
  :param $column: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: addColumnSelectionInterval($index0, $index1)

  :param $index0: :doc:`int </api_ru/.types/int>` 
  :param $index1: :doc:`int </api_ru/.types/int>` 

 .. php:method:: addRowSelectionInterval($index0, $index1)

  :param $index0: :doc:`int </api_ru/.types/int>` 
  :param $index1: :doc:`int </api_ru/.types/int>` 

 .. php:method:: getColumnName($column)

  :param $column: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: setEditingColumn($column)

  :param $column: :doc:`int </api_ru/.types/int>` 

 .. php:method:: setEditingRow($row)

  :param $row: :doc:`int </api_ru/.types/int>` 



.. include:: /api_ru.desc/php/swing/UITable.footer.rst

