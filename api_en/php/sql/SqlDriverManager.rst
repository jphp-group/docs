SqlDriverManager
------------------------

.. include:: /api_en.desc/php/sql/SqlDriverManager.header.rst

.. php:class:: php\\sql\\SqlDriverManager

 Class DriverManager



**Methods**

----------

 .. php:staticmethod:: install($driverName)

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>` if cannot install or find driver.

  :param $driverName: :doc:`string </api_en/.types/string>`  - - mysql, pgsql, postgres, mssql, firebird, sybase, sqlite, etc.

 .. php:staticmethod:: getConnection($url, $options)

  **throws** :doc:`php\\sql\\SqlException </api_en/php/sql/SqlException>` if a database access error occurs

  :param $url: :doc:`string </api_en/.types/string>` 
  :param $options: :doc:`array </api_en/.types/array>`  - (optional) username, password, etc.
  :returns: :doc:`php\\sql\\SqlConnection </api_en/php/sql/SqlConnection>` 



.. include:: /api_en.desc/php/sql/SqlDriverManager.footer.rst

