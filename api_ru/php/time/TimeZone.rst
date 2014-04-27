TimeZone
-----------------

.. include:: /api_ru.desc/php/time/TimeZone.header.rst

.. php:class:: php\\time\\TimeZone

 Class TimeZone



**Methods**

----------

 .. php:method:: __construct($rawOffset, $ID, $options = null)

  :param $rawOffset: :doc:`int </api_ru/.types/int>` 
  :param $ID: :doc:`string </api_ru/.types/string>` 
  :param $options: :doc:`array </api_ru/.types/array>` 

 .. php:method:: getId()

  Get id of the timezone

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: getRawOffset()

  Get raw offset of the timezone

  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:staticmethod:: UTC()

  Returns UTC Time zone

  :returns: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 

 .. php:staticmethod:: of($ID)

  :param $ID: :doc:`string </api_ru/.types/string>`  - code of timezone, e.g.: 'UTC'
  :returns: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 

 .. php:staticmethod:: setDefault($zone, $globally = false)

  Set default time zone for Time objects, by default - the default timezone is UTC

  :param $zone: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 
  :param $globally: :doc:`bool </api_ru/.types/bool>` 

 .. php:staticmethod:: getDefault($globally = false)

  Get default timezone

  :param $globally: :doc:`bool </api_ru/.types/bool>`  - if ``false`` - only for the current environment
  :returns: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 

 .. php:staticmethod:: getSystem()

  Get timezone of OS::
  
  TimeZone::setDefault(TimeZone::getSystem()); // set the default timezone as the system timezone

  :returns: :doc:`php\\time\\TimeZone </api_ru/php/time/TimeZone>` 

 .. php:staticmethod:: getAvailableIDs($rawOffset = null)

  Returns all available ids of timezones

  :param $rawOffset: :doc:`int </api_ru/.types/int>`, :doc:`null </api_ru/.types/null>` 
  :returns: :doc:`string[] </api_ru/.types/string>` 



.. include:: /api_ru.desc/php/time/TimeZone.footer.rst

