UIDialog
------------------

.. include:: /api_ru.desc/php/swing/UIDialog.header.rst

.. php:class:: php\\swing\\UIDialog

 **extends**: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>`


 Class UIDialog



**Properties**

----------

 .. php:attr:: modal

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: modalType

  :doc:`php\\swing\\string - modeless or document_modal or application_modal or toolkit_modal </api_ru/php/swing/string - modeless or document_modal or application_modal or toolkit_modal>`



**Methods**

----------

 .. php:method:: __construct($owner = null)

  :param $owner: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>` 

 .. php:staticmethod:: message($text, $title, $type = ::)

  Show basic message

  :param $text: 
  :param $title: 
  :param $type: 

 .. php:staticmethod:: confirm($text, $title, $optionType, $type = ::)

  :param $text: 
  :param $title: 
  :param $optionType: 
  :param $type: 
  :returns: :doc:`int </api_ru/.types/int>` 



.. include:: /api_ru.desc/php/swing/UIDialog.footer.rst

