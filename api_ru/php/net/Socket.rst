Socket
--------------

.. php:class:: php\\net\\Socket

 Class Socket

 .. php:method:: __construct($host = null, $port = null)

  :param $host: 
  :param $port: 

 .. php:method:: getOutput()

  :returns: :doc:`php\\io\\MiscStream </api_ru/php/io/MiscStream>` 

 .. php:method:: getInput()

  :returns: :doc:`php\\io\\MiscStream </api_ru/php/io/MiscStream>` 

 .. php:method:: getLocalAddress()

  :returns: :doc:`string </api_ru/string>` 

 .. php:method:: getAddress()

  :returns: :doc:`string </api_ru/string>` 

 .. php:method:: getLocalPort()

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: getPort()

  :returns: :doc:`int </api_ru/int>` 

 .. php:method:: close()


 .. php:method:: shutdownInput()


 .. php:method:: shutdownOutput()


 .. php:method:: isConnected()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isClosed()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isBound()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isInputShutdown()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: isOutputShutdown()

  :returns: :doc:`bool </api_ru/bool>` 

 .. php:method:: connect($hostname, $port, $timeout = null)

  Connects this socket to the server

  :param $hostname: 
  :param $port: 
  :param $timeout: 

 .. php:method:: bind($hostname, $port)

  Binds the socket to a local address.

  :param $hostname: 
  :param $port: 

 .. php:method:: bindDefault()


 .. php:method:: setSoTimeout($timeout)

  Enable/disable SO_TIMEOUT with the specified timeout, in
  milliseconds.

  :param $timeout: 

 .. php:method:: setSoLinger($on, $linger)

  :param $on: 
  :param $linger: 

 .. php:method:: setReuseAddress($on)

  Enable/disable the SO_REUSEADDR socket option.

  :param $on: 

 .. php:method:: setReceiveBufferSize($size)

  :param $size: 

 .. php:method:: setTcpNoDelay($on)

  :param $on: 

 .. php:method:: setKeepAlive($on)

  :param $on: 

 .. php:method:: setOOBInline($on)

  :param $on: 

 .. php:method:: setSendBufferSize($size)

  :param $size: 

 .. php:method:: setTrafficClass($tc)

  Sets traffic class or type-of-service octet in the IP
  header for packets sent from this Socket.

  :param $tc: 

 .. php:method:: setPerformancePreferences($connectTime, $latency, $bandWidth)

  Sets performance preferences for this ServerSocket.
  ! Not implemented yet for TCP/IP

  :param $connectTime: 
  :param $latency: 
  :param $bandWidth: 

 .. php:method:: sendUrgentData($data)

  Send one byte of urgent data on the socket. The byte to be sent is the lowest eight
  bits of the data parameter.

  :param $data: 

