TimeFormat
-------------------

.. include:: /api_ru.desc/php/time/TimeFormat.header.rst

.. php:class:: php\\time\\TimeFormat

 Class TimeFormat



**Methods**

----------

 .. php:method:: __construct($format, $locale = null, $formatSymbols = null)

  :param $format: :doc:`string </api_ru/.types/string>` 
  :param $locale: :doc:`php\\util\\Locale </api_ru/php/util/Locale>`  - if ``null`` then it uses the default locale
  :param $formatSymbols: :doc:`array </api_ru/.types/array>`  - [months => [...], short_months, eras, weekdays, short_weekdays, local_pattern_chars]

 .. php:method:: format($time)

  :param $time: :doc:`php\\time\\Time </api_ru/php/time/Time>` 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: parse($string, $timeZone = null)

  :param $string: :doc:`string </api_ru/.types/string>` 
  :param $timeZone: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_ru/php/time/Time>`, :doc:`null </api_ru/.types/null>` if parse error then returns ``null``



.. include:: /api_ru.desc/php/time/TimeFormat.footer.rst

