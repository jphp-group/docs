EmailBackend
---------------------

.. include:: /api_en.desc/php/mail/EmailBackend.header.rst

.. php:class:: php\\mail\\EmailBackend

 Class EmailBackend



**Properties**

----------

 .. php:attr:: hostName

  :doc:`string </api_en/.types/string>`

  The host name of the SMTP server.

 .. php:attr:: smtpPort

  :doc:`string </api_en/.types/string>`

  The listening port of the SMTP server.

 .. php:attr:: sslSmtpPort

  :doc:`string </api_en/.types/string>`

  The current SSL port used by the SMTP transport.

 .. php:attr:: sendPartial

  :doc:`bool </api_en/.types/bool>`

  Sending partial email.

 .. php:attr:: socketTimeout

  :doc:`int </api_en/.types/int>`

  The socket I/O timeout value in milliseconds.

 .. php:attr:: socketConnectionTimeout

  :doc:`int </api_en/.types/int>`

  The socket connection timeout value in milliseconds.

 .. php:attr:: sslOnConnect

  :doc:`bool </api_en/.types/bool>`

  Whether SSL/TLS encryption for the transport is currently enabled (SMTPS/POPS).

 .. php:attr:: sslCheckServerIdentity

  :doc:`bool </api_en/.types/bool>`

  Whether the server identity is checked as specified by RFC 2595.



**Methods**

----------

 .. php:method:: getHostName()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setHostName($hostName)

  **protected**


  :param $hostName: :doc:`string </api_en/.types/string>` 

 .. php:method:: getSmtpPort()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setSmtpPort($smtpPort)

  **protected**


  :param $smtpPort: :doc:`string </api_en/.types/string>` 

 .. php:method:: getSslSmtpPort()

  **protected**


  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: setSslSmtpPort($sslSmtpPort)

  **protected**


  :param $sslSmtpPort: :doc:`string </api_en/.types/string>` 

 .. php:method:: isSendPartial()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setSendPartial($sendPartial)

  **protected**


  :param $sendPartial: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: getSocketTimeout()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setSocketTimeout($socketTimeout)

  **protected**


  :param $socketTimeout: :doc:`int </api_en/.types/int>` 

 .. php:method:: getSocketConnectionTimeout()

  **protected**


  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: setSocketConnectionTimeout($socketConnectionTimeout)

  **protected**


  :param $socketConnectionTimeout: :doc:`int </api_en/.types/int>` 

 .. php:method:: isSslOnConnect()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setSslOnConnect($sslOnConnect)

  **protected**


  :param $sslOnConnect: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: isSslCheckServerIdentity()

  **protected**


  :returns: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setSslCheckServerIdentity($sslCheckServerIdentity)

  **protected**


  :param $sslCheckServerIdentity: :doc:`boolean </api_en/.types/boolean>` 

 .. php:method:: setAuthentication($login, $password)

  Sets the userName and password if authentication is needed. If this
  method is not used, no authentication will be performed.

  :param $login: :doc:`string </api_en/.types/string>` 
  :param $password: :doc:`string </api_en/.types/string>` 

 .. php:method:: clearAuthentication()




.. include:: /api_en.desc/php/mail/EmailBackend.footer.rst

