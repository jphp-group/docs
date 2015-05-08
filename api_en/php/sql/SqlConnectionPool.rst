SqlConnectionPool
-------------------------

.. include:: /api_en.desc/php/sql/SqlConnectionPool.header.rst

.. php:class:: php\\sql\\SqlConnectionPool

 Class SqlConnectionPool



**Methods**

----------

 .. php:method:: __construct($parent)

  **protected**


  :param $parent: :doc:`php\\sql\\SqlConnectionPool </api_en/php/sql/SqlConnectionPool>` 

 .. php:method:: getConnection()

  :returns: :doc:`php\\sql\\SqlConnection </api_en/php/sql/SqlConnection>` 

 .. php:method:: setUser($username)

  :param $username: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 

 .. php:method:: setPassword($password)

  :param $password: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 

 .. php:method:: setMaxPoolSize($value)

  :param $value: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 

 .. php:method:: setIdleTimeout($millis)

  :param $millis: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 

 .. php:method:: setMaxLifetime($millis)

  :param $millis: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 

 .. php:method:: setMinimumIdle($millis)

  :param $millis: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`php\\sql\\$this </api_en/php/sql/$this>` 



.. include:: /api_en.desc/php/sql/SqlConnectionPool.footer.rst

