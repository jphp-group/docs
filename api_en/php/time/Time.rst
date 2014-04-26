Time
-------------

.. include:: /api_en.desc/php/time/Time.header.rst

.. php:class:: php\\time\\Time

 Class Time, Immutable



**Methods**

----------

 .. php:method:: __construct($date, $timezone = null)

  :param $date: :doc:`int </api_en/.types/int>`  - timestamp
  :param $timezone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>`  - - if null then gets default timezone

 .. php:method:: getTime()

  Returns the number of milliseconds since January 1, 1970, 00:00:00 GMT
  represented by this Time object.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getTimeZone()

  Get timezone of the time object

  :returns: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 

 .. php:method:: year()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: month()

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

 .. php:method:: plusDays($count)

  Get a new time + day count

  :param $count: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: plusMonths($count)

  Get a new time + month count

  :param $count: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: plusYears($count)

  Get a new time + year count

  :param $count: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:staticmethod:: now($timeZone = null)

  Returns now time object

  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>` 
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:staticmethod:: of($args, $timeZone = null)

  Create a new time by using the $args arrays that can contain the ``sec``, ``min``, ``hour`` and other keys::
  
  $time = Time::of(['year' => 2013, 'month' => 1, 'day' => 1]) // 01 Jan 2013

  :param $args: :doc:`array </api_en/.types/array>`  - [sec, min, hour, day, month, year]
  :param $timeZone: :doc:`php\\time\\TimeZone </api_en/php/time/TimeZone>`  - if null then it uses the default timezone
  :returns: :doc:`php\\time\\Time </api_en/php/time/Time>` 

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

