Email
--------------

.. include:: /api_en.desc/php/mail/Email.header.rst

.. php:class:: php\\mail\\Email

 Class Email



**Methods**

----------

 .. php:method:: setFrom($email, $name, $charset)

  :param $email: :doc:`string </api_en/.types/string>` 
  :param $name: :doc:`string </api_en/.types/string>`  - (optional)
  :param $charset: :doc:`string </api_en/.types/string>`  - (optional)
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setCharset($charset)

  :param $charset: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setSubject($subject)

  :param $subject: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setTo($addresses)

  :param $addresses: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setCc($addresses)

  :param $addresses: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setBcc($addresses)

  :param $addresses: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setBounceAddress($email)

  :param $email: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setHeaders($headers)

  :param $headers: :doc:`array </api_en/.types/array>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setMessage($message)

  :param $message: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setHtmlMessage($message)

  :param $message: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: setTextMessage($message)

  :param $message: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: attach($content, $contentType, $name, $description = '')

  :param $content: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $contentType: :doc:`string </api_en/.types/string>` 
  :param $name: :doc:`string </api_en/.types/string>` 
  :param $description: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\mail\\$this </api_en/php/mail/$this>` 

 .. php:method:: send($backend)

  Sends the email. Internally we build a MimeMessage
  which is afterwards sent to the SMTP server.

  :param $backend: :doc:`php\\mail\\EmailBackend </api_en/php/mail/EmailBackend>` 
  :returns: :doc:`string </api_en/.types/string>` the message id of the underlying MimeMessage



.. include:: /api_en.desc/php/mail/Email.footer.rst

