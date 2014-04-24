UITextElement
-----------------------

.. include:: /api_ru.desc/php/swing/UITextElement.header.rst

.. php:class:: php\\swing\\UITextElement

 **abstract** class

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`

**Children**

----------------------

 * **class** :doc:`php\\swing\\UIEdit </api_ru/php/swing/UIEdit>`
 * **class** :doc:`php\\swing\\UIEditorArea </api_ru/php/swing/UIEditorArea>`
 * **class** :doc:`php\\swing\\UITextArea </api_ru/php/swing/UITextArea>`



**Properties**

----------

 .. php:attr:: text

  :doc:`string </api_ru/.types/string>`

 .. php:attr:: readOnly

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: caretPos

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: caretColor

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: selectedStart

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: selectedEnd

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: selectedText

  :doc:`int </api_ru/.types/int>`

  **read-only**


 .. php:attr:: selectionColor

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: selectionTextColor

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: disabledTextColor

  :doc:`php\\swing\\Color </api_ru/php/swing/Color>`

 .. php:attr:: margin

  :doc:`php\\swing\\array [top, left, bottom, right] </api_ru/php/swing/array [top, left, bottom, right]>`

  int[]



**Methods**

----------

 .. php:method:: copy()


 .. php:method:: cut()


 .. php:method:: paste()


 .. php:method:: select($selStart, $selEnd)

  :param $selStart: :doc:`int </api_ru/.types/int>` 
  :param $selEnd: :doc:`int </api_ru/.types/int>` 

 .. php:method:: selectAll()


 .. php:method:: replaceSelection($content)

  :param $content: :doc:`string </api_ru/.types/string>` 

 .. php:method:: printDialog()

  A convenience print method that displays a print dialog, and then
  prints this element in interactive mode with no
  header or footer text. Note: this method
  blocks until printing is done.

  :returns: :doc:`bool </api_ru/.types/bool>` 



.. include:: /api_ru.desc/php/swing/UITextElement.footer.rst

