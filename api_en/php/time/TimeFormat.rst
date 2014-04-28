TimeFormat
-------------------

.. include:: /api_en.desc/php/time/TimeFormat.header.rst

.. php:class:: php\\time\\TimeFormat

 Class TimeFormat, Immutable



**Methods**

----------

 .. php:method:: __construct($format, $locale = null, $formatSymbols = null)

  :param $format: :doc:`string </api_en/.types/string>` 
  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>`  - if ``null`` then it uses the default locale
  :param $formatSymbols: :doc:`array </api_en/.types/array>`  - [months => [...], short_months, eras, weekdays, short_weekdays, local_pattern_chars]

 .. php:method:: format($time)

  :param $time: :doc:`php\\time\\Time </api_en/php/time/Time>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: parse($string, $timeZone = null)

  :param $string: :doc:`string </api_en/.types/string>` 
  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>`, :doc:`null </api_en/.types/null>` if parse error then returns ``null``

 .. php:method:: __clone()

  **private**





.. include:: /api_en.desc/php/time/TimeFormat.footer.rst

