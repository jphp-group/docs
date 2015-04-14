Process
----------------

.. include:: /api_en.desc/php/lang/Process.header.rst

.. php:class:: php\\lang\\Process

 Class Process



**Methods**

----------

 .. php:method:: __construct($commands, $directory = null, $environment = null)

  :param $commands: :doc:`array </api_en/.types/array>` 
  :param $directory: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>` 
  :param $environment: :doc:`array </api_en/.types/array>` 

 .. php:method:: start()

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`php\\lang\\Process </api_en/php/lang/Process>` 

 .. php:method:: startAndWait()

  Causes the current thread to wait, if necessary, until the
  process represented by this `Process` object has
  terminated.  This method returns immediately if the subprocess
  has already terminated.  If the subprocess has not yet
  terminated, the calling thread will be blocked until the
  subprocess exits.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`php\\lang\\Process </api_en/php/lang/Process>` 

 .. php:method:: getExitValue()

  Returns the exit value for the subprocess.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`int </api_en/.types/int>`, :doc:`null </api_en/.types/null>` - null if process is working

 .. php:method:: destroy()

  Kills the subprocess. The subprocess represented by this
  `Process` object is forcibly terminated.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`


 .. php:method:: getInput()

  Returns the input stream connected to the normal output of the
  subprocess.  The stream obtains data piped from the standard
  output of the process represented by this `Process` object.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getOutput()

  Returns the output stream connected to the normal input of the
  subprocess.  Output to the stream is piped into the standard
  input of the process represented by this `Process` object.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 

 .. php:method:: getError()

  Returns the input stream connected to the error output of the
  subprocess.  The stream obtains data piped from the error output
  of the process represented by this `Process` object.

  **throws** :doc:`php\\lang\\IllegalStateException </api_en/php/lang/IllegalStateException>`

  :returns: :doc:`php\\io\\Stream </api_en/php/io/Stream>` 



.. include:: /api_en.desc/php/lang/Process.footer.rst

