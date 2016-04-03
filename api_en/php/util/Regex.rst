Regex
--------------

.. include:: /api_en.desc/php/util/Regex.header.rst

.. php:class:: php\\util\\Regex

 **implements**: :doc:`Iterator </api_en/Iterator>`


 http://www.regular-expressions.info/java.html
 
 Class Regex, Immutable



**Constants**

----------

 .. php:const:: CANON_EQ

 .. php:const:: CASE_INSENSITIVE

 .. php:const:: UNICODE_CASE

 .. php:const:: COMMENTS

 .. php:const:: DOTALL

 .. php:const:: LITERAL

 .. php:const:: MULTILINE

 .. php:const:: UNIX_LINES



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: getPattern()

  Get the current pattern

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getFlags()

  Get the current flags

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: of($pattern, $flag = 0)

  Creates a new Regex of regex with $string and $flag

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $pattern: :doc:`string </api_en/.types/string>`  - regular expression
  :param $flag: :doc:`int </api_en/.types/int>`  - Regex::CASE_INSENSITIVE and other constants
  :returns: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 

 .. php:method:: matches()

  Attempts to match the entire region against the pattern.

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: find($start = null)

  Resets this matcher and then attempts to find the next subsequence of
  the input sequence that matches the pattern, starting at the specified
  index.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $start: :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: replace($replacement)

  Replaces every subsequence of the input sequence that matches the
  pattern with the given replacement string.
  
  This method first resets this matcher.  It then scans the input
  sequence looking for matches of the pattern.  Characters that are not
  part of any match are appended directly to the result string; each match
  is replaced in the result by the replacement string.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $replacement: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: replaceFirst($replacement)

  Replaces the first subsequence of the input sequence that matches the
  pattern with the given replacement string.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $replacement: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: replaceGroup($group, $replacement)

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $group: :doc:`int </api_en/.types/int>` 
  :param $replacement: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: replaceWithCallback($callback)

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $callback: :doc:`callable </api_en/.types/callable>`  - (Regex $pattern) -> string
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: with($string)

  Duplicates this pattern with a new $string

  :param $string: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 

 .. php:method:: withFlags($flags)

  Clone this object with the new $flags

  :param $flags: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 

 .. php:method:: group($group = null)

  Returns the input subsequence captured by the given group during the
  previous match operation.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $group: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getGroupCount()

  Returns the number of capturing groups in this matcher's pattern.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: start($group = null)

  Returns the start index of the previous match.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $group: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: end($group = null)

  Returns the offset after the last character matched.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $group: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: hitEnd()

  Returns true if the end of input was hit by the search engine in
  the last match operation performed by this matcher.

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: requireEnd()

  Returns true if more input could change a positive match into a
  negative one.
  
  If this method returns true, and a match was found, then more
  input could cause the match to be lost. If this method returns false
  and a match was found, then more input might change the match but the
  match won't be lost. If a match was not found, then requireEnd has no
  meaning.

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: lookingAt()

  Attempts to match the input sequence, starting at the beginning of the
  region, against the pattern.

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: region($start, $end)

  Sets the limits of this matcher's region. The region is the part of the
  input sequence that will be searched to find a match. Invoking this
  method resets the matcher, and then sets the region to start at the
  index specified by the $start parameter and end at the
  index specified by the $end parameter.

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $start: :doc:`int </api_en/.types/int>` 
  :param $end: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\util\\Regex </api_en/php/util/Regex>` 

 .. php:method:: regionStart()

  Reports the start index of this matcher's region. The
  searches this matcher conducts are limited to finding matches
  within ``regionStart()`` (inclusive) and
  ``regionEnd()`` (exclusive).

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: regionEnd()

  Reports the end index (exclusive) of this matcher's region.
  The searches this matcher conducts are limited to finding matches
  within ``regionStart()`` (inclusive) and
  ``regionEnd()`` (exclusive).

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: reset($string = null)

  Resets this matcher.
  
  Resetting a matcher discards all of its explicit state information
  and sets its append position to zero. The matcher's region is set to the
  default region, which is its entire character sequence. The anchoring
  and transparency of this matcher's region boundaries are unaffected.

  :param $string: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>`  - The new input character sequence
  :returns: :doc:`php\\util\\$this </api_en/php/util/$this>` 

 .. php:method:: current()

  :returns: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: next()


 .. php:method:: key()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: rewind()


 .. php:method:: __clone()

  **private**



 .. php:staticmethod:: match($pattern, $string, $flags = 0)

  Tells whether or not this string matches the given regular expression.
  See also java.lang.String.matches()

  :param $pattern: :doc:`string </api_en/.types/string>`  - regular expression
  :param $string: :doc:`string </api_en/.types/string>` 
  :param $flags: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: split($pattern, $string, $limit = 0)

  Splits this string around matches of the given regular expression.
  See also java.lang.String.split()

  **throws** :doc:`php\\util\\RegexException </api_en/php/util/RegexException>`

  :param $pattern: :doc:`string </api_en/.types/string>`  - the delimiting regular expression
  :param $string: :doc:`string </api_en/.types/string>` 
  :param $limit: :doc:`int </api_en/.types/int>`  - the result threshold
  :returns: :doc:`array </api_en/.types/array>` the array of strings computed by splitting this string around matches of the given regular expression

 .. php:staticmethod:: quote($string)

  Returns a literal pattern ``String`` for the specified
  ``String``.
  
  
  This method produces a ``String`` that can be used to
  create a ``Regex`` that would match the string
  ``$string`` as if it were a literal pattern. Metacharacters
  or escape sequences in the input sequence will be given no special
  meaning.

  :param $string: :doc:`string </api_en/.types/string>`  - The string to be literalized
  :returns: :doc:`string </api_en/.types/string>` A literal string replacement

 .. php:staticmethod:: quoteReplacement($string)

  Returns a literal replacement ``String`` for the specified
  ``String``.
  
  This method produces a ``String`` that will work
  as a literal replacement $string in the
  replaceWithCallback() method of the ``php\util\Regex`` class.
  The ``String`` produced will match the sequence of characters
  in $string treated as a literal sequence. Slashes ('\') and
  dollar signs ('$') will be given no special meaning.

  :param $string: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/util/Regex.footer.rst

