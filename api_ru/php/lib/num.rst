num
-----------

.. php:class:: php\\lib\\num

 Utils for numbers
 Class num

 .. php:method:: __construct()

  **private**


 .. php:staticmethod:: toBin($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 2.

  :param $number: 
  :returns: :doc:`string </api_ru/string>` 

 .. php:staticmethod:: toOctal($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 8.

  :param $number: 
  :returns: :doc:`string </api_ru/string>` 

 .. php:staticmethod:: toHex($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 16.

  :param $number: 
  :returns: :doc:`string </api_ru/string>` 

 .. php:staticmethod:: toString($number, $radix)

  Returns a string representation of the first argument in the
  radix specified by the second argument.

  :param $number: 
  :param $radix: 
  :returns: :doc:`string </api_ru/string>` 

 .. php:staticmethod:: reverse($number)

  Returns the value obtained by reversing the order of the bits in the
  two's complement binary representation of the specified {@code long}
  value.

  :param $number: 
  :returns: :doc:`int </api_ru/int>` 

 .. php:staticmethod:: decode($string)

  Decodes a string into a integer.
  Accepts decimal, hexadecimal, and octal numbers

  :param $string: 
  :returns: :doc:`string </api_ru/string>` or false if invalid number format

 .. php:staticmethod:: format($number, $pattern, $decSep = '.', $groupSep = ',')

  :param $number: 
  :param $pattern: 
  :param $decSep: 
  :param $groupSep: 
  :returns: :doc:`string </api_ru/string>` 

