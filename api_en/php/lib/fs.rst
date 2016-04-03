fs
----------

.. include:: /api_en.desc/php/lib/fs.header.rst

.. php:class:: php\\lib\\fs

 File System class.
 
 Class fs



**Methods**

----------

 .. php:staticmethod:: separator()

  Return the local filesystem's name-separator character.

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: pathSeparator()

  Return the local filesystem's path-separator character.

  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: valid($name)

  Validate file name.

  :param $name: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: abs($path)

  Returns absolute real path.

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: name($path)

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: nameNoExt($path)

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: pathNoExt($path)

  Returns path without extension.

  :param $path: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: ext($path)

  Returns extension of path.

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: hasExt($path, $extensions = null, $ignoreCase = true)

  Check that $path has an extension from the extension set.

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $extensions: :doc:`string </api_en/.types/string>`, :doc:`array </api_en/.types/array>` 
  :param $ignoreCase: :doc:`bool </api_en/.types/bool>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: parent($path)

  Returns parent directory.

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: ensureParent($path)

  Checks parent of path and if it is not exists, tries to create parent directory.
  See makeDir().

  :param $path: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: normalize($path)

  Normalizes file path for current OS.

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: exists($path)

  :param $path: 
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: size($path)

  Returns size of file in bytes.

  :param $path: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: isFile($path)

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isDir($path)

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: isHidden($path)

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: time($path)

  Returns last modification time of file or directory.

  :param $path: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:staticmethod:: makeDir($path)

  Creates empty directory (mkdirs) if not exists.

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: makeFile($path)

  Creates empty file, if file already exists then rewrite it.

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: delete($path)

  Deletes file or empty directory.

  :param $path: 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: clean($path, $checker = null)

  Deletes all files in path. This method does not delete the $path directory.
  Returns array with error, success and skip file list.

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $checker: :doc:`callable </api_en/.types/callable>`  - (File $file, $depth) optional, must return true to delete the file.
  :returns: :doc:`array </api_en/.types/array>` [success => [], error => [], skip = []]

 .. php:staticmethod:: scan($path, $onProgress, $maxDepth = 0, $subIsFirst = false)

  :param $path: :doc:`string </api_en/.types/string>` 
  :param $onProgress: :doc:`callable </api_en/.types/callable>`  - (File $file, $depth)
  :param $maxDepth: :doc:`int </api_en/.types/int>`  - if 0 then unlimited.
  :param $subIsFirst: :doc:`bool </api_en/.types/bool>` 

 .. php:staticmethod:: hash($source, $algo = 'MD5')

  Calculates hash of file or stream.

  :param $source: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $algo: :doc:`string </api_en/.types/string>`  - MD5, MD2, SHA-1, SHA-256, SHA-512
  :returns: :doc:`string </api_en/.types/string>` 

 .. php:staticmethod:: copy($source, $dest, $onProgress = null)

  Copies $source stream to $dest stream.

  :param $source: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $dest: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>`, :doc:`php\\io\\Stream </api_en/php/io/Stream>` 
  :param $onProgress: :doc:`callable </api_en/.types/callable>`  - ($copiedBytes)
  :returns: :doc:`int </api_en/.types/int>` copied bytes.

 .. php:staticmethod:: get($source, $charset = null, $mode = 'r')

  Reads fully data from source and returns it as binary string.

  :param $source: :doc:`string </api_en/.types/string>` 
  :param $charset: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>`  - UTF-8, windows-1251, etc.
  :param $mode: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`string </api_en/.types/string>` 



.. include:: /api_en.desc/php/lib/fs.footer.rst

