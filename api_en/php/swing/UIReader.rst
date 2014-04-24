UIReader
------------------

.. include:: /api_en.desc/php/swing/UIReader.header.rst

.. php:class:: php\\swing\\UIReader

 Class XmlUIReader



**Methods**

----------

 .. php:method:: read($stream)

  :param $stream: :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: onRead($handle = NULL)

  :param $handle: :doc:`callable </api_en/.types/callable>`  - (UIElement $el, $var)

 .. php:method:: onTranslate($handle = NULL)

  :param $handle: :doc:`callable </api_en/.types/callable>`  - (UIElement $el, $value) -> mixed



.. include:: /api_en.desc/php/swing/UIReader.footer.rst

