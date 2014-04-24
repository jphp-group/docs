UIDialog
------------------

.. include:: /api_ru.desc/php/swing/UIDialog.header.rst

.. php:class:: php\\swing\\UIDialog

 **extends**: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>`


 Class UIDialog



**Constants**

----------

 .. php:const:: PLAIN_MESSAGE

 .. php:const:: ERROR_MESSAGE

 .. php:const:: INFORMATION_MESSAGE

 .. php:const:: WARNING_MESSAGE

 .. php:const:: QUESTION_MESSAGE

 .. php:const:: DEFAULT_OPTION

 .. php:const:: OK_CANCEL_OPTION

 .. php:const:: YES_NO_CANCEL_OPTION

 .. php:const:: YES_NO_OPTION

 .. php:const:: YES_OPTION

 .. php:const:: NO_OPTION

 .. php:const:: CANCEL_OPTION

 .. php:const:: OK_OPTION

 .. php:const:: CLOSED_OPTION



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

  :param $text: :doc:`string </api_ru/.types/string>` 
  :param $title: :doc:`string </api_ru/.types/string>` 
  :param $type: :doc:`int </api_ru/.types/int>` 

 .. php:staticmethod:: confirm($text, $title, $optionType, $type = ::)

  :param $text: :doc:`string </api_ru/.types/string>` 
  :param $title: :doc:`string </api_ru/.types/string>` 
  :param $optionType: :doc:`int </api_ru/.types/int>` 
  :param $type: :doc:`int </api_ru/.types/int>` 
  :returns: :doc:`int </api_ru/.types/int>` 



.. include:: /api_ru.desc/php/swing/UIDialog.footer.rst

