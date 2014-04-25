Pattern
---------------------

.. include:: /api_en.desc/php/lib/regex/Pattern.header.rst

.. php:class:: php\\lib\\regex\\Pattern

 **implements**: :doc:`Iterator </api_en/Iterator>`


 http://www.regular-expressions.info/java.html
 
 Class Pattern



**Constants**

----------

 .. php:const:: CANON_EQ

 .. php:const:: CASE_INSENSITIVE

 .. php:const:: UNICODE_CASE

 .. php:const:: UNICODE_CHARACTER_CLASS

 .. php:const:: COMMENTS

 .. php:const:: DOTALL

 .. php:const:: LITERAL

 .. php:const:: MULTILINE

 .. php:const:: UNIX_LINES



**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: matches()

  Attempts to match the entire region against the pattern.

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: find($start = null)

  Resets this matcher and then attempts to find the next subsequence of
  the input sequence that matches the pattern, starting at the specified
  index.

  :param $start: :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: replace($replacement)

  Replaces every subsequence of the input sequence that matches the
  pattern with the given replacement string.
  
  This method first resets this matcher.  It then scans the input
  sequence looking for matches of the pattern.  Characters that are not
  part of any match are appended directly to the result string; each match
  is replaced in the result by the replacement string.

  :param $replacement: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: replaceFirst($replacement)

  Replaces the first subsequence of the input sequence that matches the
  pattern with the given replacement string.

  :param $replacement: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: replaceWithCallback($callback)

  :param $callback: :doc:`callable </api_en/.types/callable>`  - (Pattern $pattern) -> string
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: with($string)

  Duplicates this pattern with a new $string

  :param $string: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\lib\\regex\\Pattern </api_en/php/lib/regex/Pattern>` 

 .. php:method:: group($group = null)

  Returns the input subsequence captured by the given group during the
  previous match operation.

  :param $group: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>`, :doc:`float </api_en/.types/float>`, :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getGroupCount()

  Returns the number of capturing groups in this matcher's pattern.

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: start($group = null)

  Returns the start index of the previous match.

  :param $group: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: end($group = null)

  Returns the offset after the last character matched.

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

  :param $start: :doc:`int </api_en/.types/int>` 
  :param $end: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\lib\\regex\\Pattern </api_en/php/lib/regex/Pattern>` 

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
  :returns: :doc:`php\\lib\\regex\\$this </api_en/php/lib/regex/$this>` 

 .. php:staticmethod:: of($pattern, $string = '', $flag = 0)

  Creates a new Pattern of regex with $string and $flag

  :param $pattern: :doc:`string </api_en/.types/string>`  - regular expression
  :param $string: :doc:`string </api_en/.types/string>` 
  :param $flag: :doc:`int </api_en/.types/int>`  - Pattern::CASE_INSENSITIVE and other constants
  :returns: :doc:`php\\lib\\regex\\Pattern </api_en/php/lib/regex/Pattern>` 

 .. php:method:: current()

  :returns: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: next()

  :returns: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: key()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: rewind()

  :returns: :doc:`bool </api_en/.types/bool>` 



.. include:: /api_en.desc/php/lib/regex/Pattern.footer.rst

