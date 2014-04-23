UITable
-----------------

.. include:: /api_en.desc/php/swing/UITable.header.rst

.. php:class:: php\\swing\\UITable

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 Class UITable



**Properties**

----------

 .. php:attr:: dragEnabled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: selectionBackground

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: selectionForeground

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: gridColor

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: editingColumn

  :doc:`int </api_en/.types/int>`

 .. php:attr:: editingRow

  :doc:`int </api_en/.types/int>`

 .. php:attr:: rowMargin

  :doc:`int </api_en/.types/int>`



**Methods**

----------

 .. php:method:: setRowHeight($height, $row = null)

  :param $height: 
  :param $row: 

 .. php:method:: getRowHeight($row = null)

  :param $row: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setValueAt($value, $row, $column)

  :param $value: 
  :param $row: 
  :param $column: 

 .. php:method:: getValueAt($row, $column)

  :param $row: 
  :param $column: 
  :returns: :doc:`string </api_en/.types/string>`, :doc:`null </api_en/.types/null>` 

 .. php:method:: columnAtPoint($x, $y)

  :param $x: 
  :param $y: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: rowAtPoint($x, $y)

  :param $x: 
  :param $y: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: editCellAt($row, $column)

  :param $row: 
  :param $column: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: addColumnSelectionInterval($index0, $index1)

  :param $index0: 
  :param $index1: 

 .. php:method:: addRowSelectionInterval($index0, $index1)

  :param $index0: 
  :param $index1: 

 .. php:method:: getColumnName($column)

  :param $column: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setEditingColumn($column)

  :param $column: 

 .. php:method:: setEditingRow($row)

  :param $row: 



.. include:: /api_en.desc/php/swing/UITable.footer.rst

