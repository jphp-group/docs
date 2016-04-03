SourceMap
------------------

.. include:: /api_en.desc/php/lang/SourceMap.header.rst

.. php:class:: php\\lang\\SourceMap

 Class SourceMap



**Methods**

----------

 .. php:method:: __construct($moduleName)

  :param $moduleName: :doc:`string </api_en/.types/string>` 

 .. php:method:: getModuleName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getSourceLine($compiledLine)

  :param $compiledLine: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` -1 if not found

 .. php:method:: getCompiledLine($sourceLine)

  :param $sourceLine: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`int </api_en/.types/int>` -1 if not found

 .. php:method:: insertLines($inserts, $allCountLines)

  :param $inserts: :doc:`array </api_en/.types/array>`  - int[][2] [[line, lineCount], [line, lineCount], ...]
  :param $allCountLines: :doc:`int </api_en/.types/int>`  - original source line count.

 .. php:method:: addLine($sourceLine, $compiledLine)

  :param $sourceLine: :doc:`int </api_en/.types/int>` 
  :param $compiledLine: :doc:`int </api_en/.types/int>` 

 .. php:method:: clear()


 .. php:method:: toArray()

  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/lang/SourceMap.footer.rst

