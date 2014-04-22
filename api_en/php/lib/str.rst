str
-----------

.. php:class:: php\\lib\\str

 Class str

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: ord($char)

  :param $char: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: char($code)

  :param $code: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: pos($string, $search, $fromIndex = 0)

  :param $string: 
  :param $search: 
  :param $fromIndex: 
  :returns: :doc:`int </api_en/.types/int>` - returns -1 if not found

 .. php:staticmethod:: posIgnoreCase($string, $search, $fromIndex = 0)

  :param $string: 
  :param $search: 
  :param $fromIndex: 
  :returns: :doc:`int </api_en/.types/int>` - returns -1 if not found

 .. php:staticmethod:: lastPos($string, $search, $fromIndex = null)

  :param $string: 
  :param $search: 
  :param $fromIndex: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` - null means $fromIndex will be equal $string.length
  :returns: :doc:`int </api_en/.types/int>` - returns -1 if not found

 .. php:staticmethod:: lastPosIgnoreCase($string, $search, $fromIndex = null)

  :param $string: 
  :param $search: 
  :param $fromIndex: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` - null means $fromIndex will be equal $string.length
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: sub($string, $beginIndex, $endIndex = null)

  :param $string: 
  :param $beginIndex: 
  :param $endIndex: 
  :returns: :doc:`string </api_en/.types/string>` - return false if params are invalid

 .. php:staticmethod:: compare($string1, $string2)

  :param $string1: 
  :param $string2: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: compareIgnoreCase($string1, $string2)

  :param $string1: 
  :param $string2: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: equalsIgnoreCase($string1, $string2)

  :param $string1: 
  :param $string2: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: matches($string, $pattern)

  :param $string: 
  :param $pattern: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: startsWith($string, $prefix, $offset = 0)

  :param $string: 
  :param $prefix: 
  :param $offset: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: endsWith($string, $suffix)

  :param $string: 
  :param $suffix: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: lower($string)

  To lower case

  :param $string: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: upper($string)

  To upper case

  :param $string: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: hash($string)

  Returns a hash code of $string

  :param $string: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: length($string)

  :param $string: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: replace($string, $target, $replacement)

  :param $string: 
  :param $target: 
  :param $replacement: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: repeat($string, $amount)

  :param $string: 
  :param $amount: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: trim($string)

  :param $string: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: reverse($string)

  :param $string: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: shuffle($string)

  Returns a randomized string based on chars in $string

  :param $string: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: split($string, $separator, $limit = 0)

  :param $string: 
  :param $separator: 
  :param $limit: 
  :returns: :doc:`php\\util\\Cursor </api_en/php/util/Cursor>` 

 .. php:staticmethod:: join($iterable, $separator, $limit = 0)

  :param $iterable: 
  :param $separator: 
  :param $limit: 
  :returns: :doc:`string </api_en/.types/string>` 

