UIAbstractIButton
---------------------------

.. include:: /api_en.desc/php/swing/UIAbstractIButton.header.rst

.. php:class:: php\\swing\\UIAbstractIButton

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`

**Children**

----------------------

 * **class** :doc:`php\\swing\\UIButton </api_en/php/swing/UIButton>`
 * **class** :doc:`php\\swing\\UICheckbox </api_en/php/swing/UICheckbox>`
 * **class** :doc:`php\\swing\\UIMenuItem </api_en/php/swing/UIMenuItem>`
 * **class** :doc:`php\\swing\\UIToggleButton </api_en/php/swing/UIToggleButton>`

 Class UIAbstractIButton



**Properties**

----------

 .. php:attr:: text

  :doc:`string </api_en/.types/string>`

  Text of button

 .. php:attr:: selected

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: verPosition

  :doc:`int </api_en/.types/int>`

  Direction

 .. php:attr:: horPosition

  :doc:`int </api_en/.types/int>`

  Direction

 .. php:attr:: verAlignment

  :doc:`int </api_en/.types/int>`

  Direction

 .. php:attr:: horAlignment

  :doc:`php\\swing\\int|string </api_en/php/swing/int|string>`

  Direction

 .. php:attr:: iconTextGap

  :doc:`int </api_en/.types/int>`

 .. php:attr:: borderPainted

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: focusPainted

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: rolloverEnabled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: contentAreaFilled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: buttonGroup

  :doc:`string </api_en/.types/string>`



**Methods**

----------

 .. php:method:: setIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>`  - - filename or Image

 .. php:method:: setDisabledIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: setSelectedIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: setPressedIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: setRolloverIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: setDisabledSelectedIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: setRolloverSelectedIcon($icon)

  :param $icon: :doc:`php\\swing\\Image </api_en/php/swing/Image>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: doClick($pressTime = 68)

  :param $pressTime: :doc:`int </api_en/.types/int>`  - the time to "hold down" the button, in milliseconds

 .. php:staticmethod:: getButtons($buttonGroup)

  :param $buttonGroup: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIAbstractIButton[] </api_en/php/swing/UIAbstractIButton>` 

 .. php:staticmethod:: getSelectedButtons($buttonGroup)

  :param $buttonGroup: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIAbstractIButton[] </api_en/php/swing/UIAbstractIButton>` 



.. include:: /api_en.desc/php/swing/UIAbstractIButton.footer.rst

