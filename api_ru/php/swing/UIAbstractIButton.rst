UIAbstractIButton
---------------------------

.. include:: /api_ru.desc/php/swing/UIAbstractIButton.header.rst

.. php:class:: php\\swing\\UIAbstractIButton

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`


 Class UIAbstractIButton



**Properties**

----------

 .. php:attr:: text

  :doc:`string </api_ru/.types/string>`

  Text of button

 .. php:attr:: selected

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: verPosition

  :doc:`int </api_ru/.types/int>`

  Direction

 .. php:attr:: horPosition

  :doc:`int </api_ru/.types/int>`

  Direction

 .. php:attr:: verAlignment

  :doc:`int </api_ru/.types/int>`

  Direction

 .. php:attr:: horAlignment

  :doc:`php\\swing\\int|string </api_ru/php/swing/int|string>`

  Direction

 .. php:attr:: iconTextGap

  :doc:`int </api_ru/.types/int>`

 .. php:attr:: borderPainted

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: focusPainted

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: rolloverEnabled

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: contentAreaFilled

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: buttonGroup

  :doc:`string </api_ru/.types/string>`



**Methods**

----------

 .. php:method:: setIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_ru/php/swing/Image>`, :doc:`string </api_ru/.types/string>` - filename or Image

 .. php:method:: setDisabledIcon($icon)

  :param $icon: 

 .. php:method:: setSelectedIcon($icon)

  :param $icon: 

 .. php:method:: setPressedIcon($icon)

  :param $icon: 

 .. php:method:: setRolloverIcon($icon)

  :param $icon: 

 .. php:method:: setDisabledSelectedIcon($icon)

  :param $icon: 

 .. php:method:: setRolloverSelectedIcon($icon)

  :param $icon: 

 .. php:method:: doClick($pressTime = 68)

  :param $pressTime: :doc:`int </api_ru/.types/int>` the time to "hold down" the button, in milliseconds

 .. php:staticmethod:: getButtons($buttonGroup)

  :param $buttonGroup: 
  :returns: :doc:`php\\swing\\UIAbstractIButton[] </api_ru/php/swing/UIAbstractIButton>` 

 .. php:staticmethod:: getSelectedButtons($buttonGroup)

  :param $buttonGroup: 
  :returns: :doc:`php\\swing\\UIAbstractIButton[] </api_ru/php/swing/UIAbstractIButton>` 



.. include:: /api_ru.desc/php/swing/UIAbstractIButton.footer.rst

