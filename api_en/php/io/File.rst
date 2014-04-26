File
-----------

.. include:: /api_en.desc/php/io/File.header.rst

.. php:class:: php\\io\\File

 Class File



**Constants**

----------

 .. php:const:: PATH_SEPARATOR

 .. php:const:: DIRECTORY_SEPARATOR

 .. php:const:: PATH_NAME_CASE_INSENSITIVE



**Methods**

----------

 .. php:method:: __construct($path, $child = NULL)

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $child: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 

 .. php:method:: exists()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: canExecute()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: canWrite()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: canRead()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getName()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getAbsolutePath()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getCanonicalPath()

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getParent()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getPath()

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:method:: getAbsoluteFile()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: getCanonicalFile()

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: getParentFile()

  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: mkdir()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: mkdirs()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isFile()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isDirectory()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isAbsolute()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isHidden()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: delete()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: deleteOnExit()

  :returns: :doc:`void </api_en/.types/void>` 

 .. php:method:: createNewFile()

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: lastModified()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: length()

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: renameTo($newName)

  :param $newName: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setExecutable($value, $ownerOnly = true)

  :param $value: :doc:`bool </api_en/.types/bool>` 
  :param $ownerOnly: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setWritable($value, $ownerOnly = true)

  :param $value: :doc:`bool </api_en/.types/bool>` 
  :param $ownerOnly: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setReadable($value, $ownerOnly = true)

  :param $value: :doc:`bool </api_en/.types/bool>` 
  :param $ownerOnly: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setReadOnly()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setLastModified($time)

  :param $time: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: compareTo($file)

  :param $file: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>` 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: find($filter = null)

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :param $filter: :doc:`callable </api_en/.types/callable>` 
  :returns: :doc:`string[] </api_en/.types/string>` 

 .. php:method:: findFiles($filter = null)

  **throws** :doc:`php\\io\\IOException </api_en/php/io/IOException>`

  :param $filter: :doc:`callable </api_en/.types/callable>` 
  :returns: :doc:`php\\io\\File[] </api_en/php/io/File>` 

 .. php:staticmethod:: createTemp($prefix, $suffix, $directory = null)

  :param $prefix: :doc:`string </api_en/.types/string>` 
  :param $suffix: :doc:`string </api_en/.types/string>` 
  :param $directory: :doc:`null </api_en/.types/null>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:staticmethod:: listRoots()

  List the available filesystem roots.
  Returns an array of objects denoting the available filesystem roots,
  or empty array if the set of roots could not be determined.
  The array will be empty if there are no filesystem roots.

  :returns: :doc:`php\\io\\File[] </api_en/php/io/File>` 



.. include:: /api_en.desc/php/io/File.footer.rst

