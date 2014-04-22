UITextElement
-----------------------

.. php:class:: php\\swing\\UITextElement

 **abstract** class

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 .. php:method:: copy()


 .. php:method:: cut()


 .. php:method:: paste()


 .. php:method:: select($selStart, $selEnd)

  :param $selStart: 
  :param $selEnd: 

 .. php:method:: selectAll()


 .. php:method:: replaceSelection($content)

  :param $content: 

 .. php:method:: printDialog()

  A convenience print method that displays a print dialog, and then
  prints this element in interactive mode with no
  header or footer text. Note: this method
  blocks until printing is done.

  :returns: :doc:`bool </api_en/bool>` 

