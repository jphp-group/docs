Flow
-------------

.. php:class:: php\\util\\Flow

 **implements**: :doc:`Iterator </api_ru/Iterator>`


 Class Flow

 .. php:method:: __construct($collection)

  :param $collection: 

 .. php:method:: withKeys()

  Enables to save keys for the next operation

  :returns: :doc:`php\\util\\$this </api_ru/php/util/$this>` 

 .. php:method:: append($collection)

  :param $collection: 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: find($filter = null)

  :param $filter: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: findOne($filter = null)

  :param $filter: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: group($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: each($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` ($el[, $key]): bool
  :returns: :doc:`int </api_ru/.types/int>` - iteration count

 .. php:method:: eachSlice($sliceSize, $callback, $withKeys = false)

  :param $sliceSize: 
  :param $callback: :doc:`callable </api_ru/.types/callable>` (array $items): bool
  :param $withKeys: 
  :returns: :doc:`int </api_ru/.types/int>` - slice iteration count

 .. php:method:: map($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` ($el[, $key])
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: skip($n)

  :param $n: :doc:`int </api_ru/.types/int>` - skip count
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: limit($count)

  :param $count: 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:method:: reduce($callback)

  :param $callback: :doc:`callable </api_ru/.types/callable>` ($result, $el[, $key])
  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: toArray()

  :returns: :doc:`array </api_ru/.types/array>` 

 .. php:method:: toString($separator)

  :param $separator: 
  :returns: :doc:`string </api_ru/.types/string>` 

 .. php:method:: count()

  :returns: :doc:`int </api_ru/.types/int>` 

 .. php:method:: current()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: next()

  :returns: :doc:`void </api_ru/.types/void>` 

 .. php:method:: key()

  :returns: :doc:`mixed </api_ru/.types/mixed>` 

 .. php:method:: valid()

  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: rewind()

  :returns: :doc:`void </api_ru/.types/void>` 

 .. php:staticmethod:: of($collection)

  :param $collection: 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:staticmethod:: ofRange($from, $to, $step = 1)

  :param $from: 
  :param $to: 
  :param $step: 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

 .. php:staticmethod:: ofString($string, $chunkSize = 1)

  :param $string: 
  :param $chunkSize: 
  :returns: :doc:`php\\util\\Flow </api_ru/php/util/Flow>` 

