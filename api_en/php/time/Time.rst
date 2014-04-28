Time
-------------

.. include:: /api_en.desc/php/time/Time.header.rst

.. php:class:: php\\time\\Time

 Class Time, Immutable



**Methods**

----------

 .. php:method:: __construct($date, $timezone = null)

  :param $date: :doc:`int </api_en/.types/int>`  - unix long timestamp (in millis)
  :param $timezone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>`  - - if null then gets default timezone

 .. php:method:: getTime()

  Returns the number of milliseconds since January 1, 1970, 00:00:00 GMT
  represented by this Time object.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getTimeZone()

  Get timezone of the time object

  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:method:: year()

  Get the current year

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: month()

  Get the current month of the year, 1 - Jan, 12 - Dec

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: week()

  Get week of year

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: weekOfMonth()

  Get week of month

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: day()

  Get day of year

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: dayOfMonth()

  Get day of month

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: dayOfWeek()

  Get day of week

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: dayOfWeekInMonth()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: hour()

  Get hour, indicating the hour of the morning or afternoon.
  hour() is used for the 12-hour clock (0 - 11). Noon and midnight are represented by 0, not by 12.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: hourOfDay()

  Get hour of the day

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: minute()

  Get minute of the hour

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: second()

  Get second of the minute

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: millisecond()

  Get millisecond of the second

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: compare($time)

  Compares the time values
  
  Returns the value ``0`` if the time represented by the argument
  is equal to the time represented by this ``Time``; a value
  less than ``0`` if the time of this ``Time`` is
  before the time represented by the argument; and a value greater than
  ``0`` if the time of this ``Time`` is after the
  time represented by the argument.

  :param $time: :doc:`php\\time\\Time </api_en/php/time/Time>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: withTimeZone($timeZone)

  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: add($args)

  Get a new time + $args
  
  .. note::
  
  use negative values to minus

  :param $args: :doc:`array </api_en/.types/array>`  - [millis, sec, min, hour, day, month, year]
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: replace($args)

  Clones the current datetime and replaces some fields to new values $args

  :param $args: :doc:`array </api_en/.types/array>`  - [millis, sec, min, hour, day, month, year]
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: toString($format)

  Format the current datetime to string with $format
  
  - G 	Era designator 	Text 	AD
  - y 	Year 	Year 	1996; 96
  - M 	Month in year 	Month 	July; Jul; 07
  - w 	Week in year 	Number 	27
  - W 	Week in month 	Number 	2
  - D 	Day in year 	Number 	189
  - d 	Day in month 	Number 	10
  - F 	Day of week in month 	Number 	2
  - E 	Day in week 	Text 	Tuesday; Tue
  - a 	Am/pm marker 	Text 	PM
  - H 	Hour in day (0-23) 	Number 	0
  - k 	Hour in day (1-24) 	Number 	24
  - K 	Hour in am/pm (0-11) 	Number 	0
  - h 	Hour in am/pm (1-12) 	Number 	12
  - m 	Minute in hour 	Number 	30
  - s 	Second in minute 	Number 	55
  - S 	Millisecond 	Number 	978
  - z 	Time zone 	General time zone 	Pacific Standard Time; PST; GMT-08:00
  - Z 	Time zone 	RFC 822 time zone 	-0800

  :param $format: :doc:`string </api_en/.types/string>`  - date time format
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: __toString()

  Format the time to yyyy-MM-dd'T'HH:mm:ss

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: __clone()

  **private**



 .. php:staticmethod:: now($timeZone = null)

  Returns now time object (date + time)

  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:staticmethod:: today($timeZone = null)

  Returns today date (without time)

  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:staticmethod:: of($args, $timeZone = null)

  Create a new time by using the $args arrays that can contain the ``sec``, ``min``, ``hour`` and other keys::
  
  $time = Time::of(['year' => 2013, 'month' => 1, 'day' => 1]) // 01 Jan 2013

  :param $args: :doc:`array </api_en/.types/array>`  - [millis, sec, min, hour, day, month, year]
  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>`  - if null then it uses the default timezone
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:staticmethod:: seconds()

  Returns the current time in seconds (like the ``millis()`` method only in seconds)

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: millis()

  Returns the current time in milliseconds.  Note that
  while the unit of time of the return value is a millisecond,
  the granularity of the value depends on the underlying
  operating system and may be larger.  For example, many
  operating systems measure time in units of tens of
  milliseconds.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: nanos()

  Returns the current value of the running Java Virtual Machine's
  high-resolution time source, in nanoseconds.
  
  This method can only be used to measure elapsed time and is
  not related to any other notion of system or wall-clock time.
  The value returned represents nanoseconds since some fixed but
  arbitrary *origin* time (perhaps in the future, so values
  may be negative).  The same origin is used by all invocations of
  this method in an instance of a Java virtual machine; other
  virtual machine instances are likely to use a different origin

  :returns: :doc:`int </api_en/.types/int>` 



.. include:: /api_en.desc/php/time/Time.footer.rst

