num
-----------

.. include:: /api_en.desc/php/lib/num.header.rst

.. php:class:: php\\lib\\num

 Utils for numbers
 
 Class num



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:staticmethod:: compare($num1, $num2)

  Compare two numbers
  
  .. note:: it can be used as comparator for number sorting

  :param $num1: :doc:`int </api_en/.types/int>`, :doc:`double </api_en/.types/double>` 
  :param $num2: :doc:`int </api_en/.types/int>`, :doc:`double </api_en/.types/double>` 
  :returns: :doc:`int </api_en/.types/int>` 0 if are equal, 1 if $num1 > $num2, -1 if $num1 < $num2

 .. php:staticmethod:: toBin($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 2.

  :param $number: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: toOctal($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 8.

  :param $number: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: toHex($number)

  Returns a string representation of the $number
  argument as an unsigned integer in base 16.

  :param $number: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: toString($number, $radix)

  Returns a string representation of the first argument in the
  radix specified by the second argument.

  :param $number: :doc:`int </api_en/.types/int>` 
  :param $radix: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: reverse($number)

  Returns the value obtained by reversing the order of the bits in the
  two's complement binary representation of the specified {@code long}
  value.

  :param $number: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: decode($string)

  Decodes a string into a integer.
  Accepts decimal, hexadecimal, and octal numbers

  :param $string: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` or false if invalid number format

 .. php:staticmethod:: format($number, $pattern, $decSep = '.', $groupSep = ',')

  :param $number: :doc:`int </api_en/.types/int>`, :doc:`double </api_en/.types/double>` 
  :param $pattern: 
  :param $decSep: :doc:`string </api_en/.types/string>` 
  :param $groupSep: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/lib/num.footer.rst

