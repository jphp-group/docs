TimeZone
-----------------

.. include:: /api_en.desc/php/time/TimeZone.header.rst

.. php:class:: php\\time\\TimeZone

 Class TimeZone



**Methods**

----------

 .. php:method:: __construct($rawOffset, $ID, $options = null)

  :param $rawOffset: :doc:`int </api_en/.types/int>` 
  :param $ID: :doc:`string </api_en/.types/string>` 
  :param $options: :doc:`array </api_en/.types/array>` 

 .. php:method:: getId()

  Get id of the timezone

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getRawOffset()

  Get raw offset of the timezone

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: UTC()

  Returns UTC Time zone

  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:staticmethod:: of($ID)

  :param $ID: :doc:`string </api_en/.types/string>`  - code of timezone, e.g.: 'UTC'
  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:staticmethod:: setDefault($zone)

  Set default time zone for Time objects, by default - the default timezone is UTC

  :param $zone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:staticmethod:: getDefault()

  Get default timezone

  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:staticmethod:: getSystem()

  Get timezone of OS::
  
  TimeZone::setDefault(TimeZone::getSystem()); // set the default timezone as the system timezone

  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:staticmethod:: getAvailableIDs($rawOffset = null)

  Returns all available ids of timezones

  :param $rawOffset: :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` 
  :returns: :doc:`string[] </api_en/.types/string>` 



.. include:: /api_en.desc/php/time/TimeZone.footer.rst

