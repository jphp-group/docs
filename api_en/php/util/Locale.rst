Locale
---------------

.. include:: /api_en.desc/php/util/Locale.header.rst

.. php:class:: php\\util\\Locale

 Class Locale, Immutable



**Methods**

----------

 .. php:method:: __construct($lang, $country = '', $variant = '')

  :param $lang: :doc:`string </api_en/.types/string>` 
  :param $country: :doc:`string </api_en/.types/string>` 
  :param $variant: :doc:`string </api_en/.types/string>` 

 .. php:method:: getLanguage()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getDisplayLanguage($locale = null)

  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getCountry()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getDisplayCountry($locale = null)

  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getVariant()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getDisplayVariant($locale = null)

  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getISO3Country()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getISO3Language()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: __toString()

  Returns a string representation of this Locale
  object, consisting of language, country, variant, script,
  and extensions as below::
  
  language + "_" + country + "_" + (variant + "_#" | "#") + script + "-" + extensions

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: __clone()

  **private**



 .. php:staticmethod:: ENGLISH()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: US()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: UK()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: CANADA()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: CANADA_FRENCH()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: FRENCH()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: FRANCE()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: ITALIAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: ITALY()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: GERMAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: GERMANY()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: JAPAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: JAPANESE()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: KOREA()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: KOREAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: CHINA()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: CHINESE()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: TAIWAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: RUSSIAN()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: RUSSIA()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: ROOT()

  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: getDefault($globally = false)

  Get default locale (if globally = false - only for the current environment)

  :param $globally: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 

 .. php:staticmethod:: setDefault($locale, $globally = false)

  Set default locale

  :param $locale: :doc:`php\\util\\Locale </api_en/php/util/Locale>` 
  :param $globally: :doc:`bool </api_en/.types/bool>`  - if ``false`` - only for the current environment

 .. php:staticmethod:: getAvailableLocales()

  Returns an array of all installed locales.
  The returned array represents the union of locales supported
  by the Java runtime environment

  :returns: :doc:`php\\util\\Locale[] </api_en/php/util/Locale>` An array of installed locales.



.. include:: /api_en.desc/php/util/Locale.footer.rst

