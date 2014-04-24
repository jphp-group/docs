UIReader
------------------

.. include:: /api_ru.desc/php/swing/UIReader.header.rst

.. php:class:: php\\swing\\UIReader

 Class XmlUIReader



**Methods**

----------

 .. php:method:: read($stream)

  :param $stream: :doc:`php\\io\\Stream </api_ru/php/io/Stream>`, :doc:`php\\io\\File </api_ru/php/io/File>`, :doc:`string </api_ru/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement </api_ru/php/swing/UIElement>` 

 .. php:method:: onRead($handle = NULL)

  :param $handle: :doc:`callable </api_ru/.types/callable>`  - (UIElement $el, $var)

 .. php:method:: onTranslate($handle = NULL)

  :param $handle: :doc:`callable </api_ru/.types/callable>`  - (UIElement $el, $value) -> mixed



.. include:: /api_ru.desc/php/swing/UIReader.footer.rst

