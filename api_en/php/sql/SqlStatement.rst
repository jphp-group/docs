SqlStatement
--------------------

.. include:: /api_en.desc/php/sql/SqlStatement.header.rst

.. php:class:: php\\sql\\SqlStatement

 **abstract** class

 **implements**: :doc:`Iterator </api_en/Iterator>`




**Methods**

----------

 .. php:method:: bind($index, $value)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $value: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: bindDate($index, $time)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $time: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: bindTime($index, $time)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $time: :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: bindTimestamp($index, $time)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $time: :doc:`php\\time\\Time </api_en/php/time/Time>`, :doc:`int </api_en/.types/int>` 

 .. php:method:: bindBlob($index, $blob)

  :param $index: :doc:`int </api_en/.types/int>` 
  :param $blob: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: fetch()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :returns: :doc:`php\\sql\\SqlResult </api_en/php/sql/SqlResult>` 

 .. php:method:: update()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getLastInsertId()

  :returns: :doc:`mixed </api_en/.types/mixed>` 

 .. php:method:: getGeneratedKeys()

  :returns: :doc:`php\\sql\\SqlResult </api_en/php/sql/SqlResult>` 

 .. php:method:: current()

  :returns: :doc:`php\\sql\\SqlResult </api_en/php/sql/SqlResult>` 

 .. php:method:: next()


 .. php:method:: key()


 .. php:method:: valid()


 .. php:method:: rewind()




.. include:: /api_en.desc/php/sql/SqlStatement.footer.rst

