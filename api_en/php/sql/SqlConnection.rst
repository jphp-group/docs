SqlConnection
---------------------

.. include:: /api_en.desc/php/sql/SqlConnection.header.rst

.. php:class:: php\\sql\\SqlConnection

 **abstract** class




**Constants**

----------

 .. php:const:: TRANSACTION_READ_UNCOMMITTED

 .. php:const:: TRANSACTION_READ_COMMITTED

 .. php:const:: TRANSACTION_REPEATABLE_READ

 .. php:const:: TRANSACTION_NONE

 .. php:const:: TRANSACTION_SERIALIZABLE



**Properties**

----------

 .. php:attr:: autoCommit

  :doc:`bool </api_en/.types/bool>`

  Disable this to use transaction mode.

 .. php:attr:: readOnly

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: transactionIsolation

  :doc:`int </api_en/.types/int>`

  See SqlConnection::TRANSACTION_* constants

 .. php:attr:: catalog

  :doc:`string </api_en/.types/string>`

 .. php:attr:: schema

  :doc:`string </api_en/.types/string>`



**Methods**

----------

 .. php:method:: identifier($name)

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`

  :param $name: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: query($sql, $arguments = null)

  :param $sql: :doc:`string </api_en/.types/string>` 
  :param $arguments: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\sql\\SqlStatement </api_en/php/sql/SqlStatement>` 

 .. php:method:: commit()

  Makes all changes made since the previous
  commit/rollback permanent and releases any database locks
  currently held by this Connection object.

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`


 .. php:method:: rollback()

  Undoes all changes made in the current transaction
  and releases any database locks currently held
  by this Connection object.

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`


 .. php:method:: close()

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>`


 .. php:method:: getCatalogs()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: getSchemas()

  :returns: :doc:`array </api_en/.types/array>` 

 .. php:method:: getMetaData()

  :returns: :doc:`array </api_en/.types/array>` 



.. include:: /api_en.desc/php/sql/SqlConnection.footer.rst

