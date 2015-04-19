SqlResult
-----------------

.. include:: /api_en.desc/php/sql/SqlResult.header.rst

.. php:class:: php\\sql\\SqlResult

 **abstract** class




**Methods**

----------

 .. php:method:: isLast()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isFirst()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: delete()

  Deletes current row.

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`


 .. php:method:: isDeleted()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: refresh()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`


 .. php:method:: get($column)

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :param $column: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`mixed </api_en/.types/mixed>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>`, :doc:`php\\time\\Time </api_en/php/time/Time>` 

 .. php:method:: toArray($assoc = true)

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :param $assoc: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/sql/SqlResult.footer.rst

