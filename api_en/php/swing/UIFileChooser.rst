UIFileChooser
-----------------------

.. include:: /api_en.desc/php/swing/UIFileChooser.header.rst

.. php:class:: php\\swing\\UIFileChooser

 **extends**: :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`


 Class UIFileChooser



**Constants**

----------

 .. php:const:: FILES_ONLY

 .. php:const:: DIRECTORIES_ONLY

 .. php:const:: FILES_AND_DIRECTORIES



**Properties**

----------

 .. php:attr:: dialogTitle

  :doc:`string </api_en/.types/string>`

 .. php:attr:: approveButtonText

  :doc:`string </api_en/.types/string>`

 .. php:attr:: selectedFile

  :doc:`php\\io\\File </api_en/php/io/File>`

 .. php:attr:: selectedFiles

  :doc:`php\\swing\\File[] </api_en/php/swing/File>`

 .. php:attr:: multiSelection

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: selectionMode

  :doc:`int </api_en/.types/int>`

  Example: FILES_AND_DIRECTORIES, FILES_ONLY or DIRECTORIES_ONLY

 .. php:attr:: dragEnabled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: fileHiding

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: controlButtonVisible

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: acceptAllFileFilterUsed

  :doc:`bool </api_en/.types/bool>`



**Methods**

----------

 .. php:method:: showDialog($approveButtonText, $parent = null)

  :param $approveButtonText: :doc:`string </api_en/.types/string>` 
  :param $parent: :doc:`php\\swing\\UIWindow </api_en/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: showSaveDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api_en/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: showOpenDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api_en/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: addChoosableFilter($filter, $description)

  :param $filter: :doc:`callable </api_en/.types/callable>`  - (File $file) -> bool
  :param $description: :doc:`string </api_en/.types/string>` 

 .. php:method:: addChoosableExtensions($extensions, $description, $showDirectories = true)

  :param $extensions: :doc:`array </api_en/.types/array>`  - ['jpg', 'gif', 'png', ... etc]
  :param $description: :doc:`string </api_en/.types/string>` 
  :param $showDirectories: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: resetChoosableFilters()


 .. php:method:: isTraversable($file)

  :param $file: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: ensureFileIsVisible($file)

  :param $file: :doc:`string </api_en/.types/string>`, :doc:`php\\io\\File </api_en/php/io/File>` 

 .. php:method:: approveSelection()


 .. php:method:: cancelSelection()


 .. php:method:: changeToParentDirectory()


 .. php:method:: onFileView($field, $callback = null)

  :param $field: :doc:`string </api_en/.types/string>`  - - name (string), description (string), icon (Image), traversable (bool)
  :param $callback: :doc:`callable </api_en/.types/callable>`  - (File $file)



.. include:: /api_en.desc/php/swing/UIFileChooser.footer.rst

