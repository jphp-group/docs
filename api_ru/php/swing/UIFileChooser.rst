UIFileChooser
-----------------------

.. include:: /api_ru.desc/php/swing/UIFileChooser.header.rst

.. php:class:: php\\swing\\UIFileChooser

 **extends**: :doc:`php\\swing\\UIContainer </api_ru/php/swing/UIContainer>`


 Class UIFileChooser



**Properties**

----------

 .. php:attr:: dialogTitle

  :doc:`string </api_ru/.types/string>`

 .. php:attr:: approveButtonText

  :doc:`string </api_ru/.types/string>`

 .. php:attr:: selectedFile

  :doc:`php\\io\\File </api_ru/php/io/File>`

 .. php:attr:: selectedFiles

  :doc:`php\\swing\\File[] </api_ru/php/swing/File>`

 .. php:attr:: multiSelection

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: selectionMode

  :doc:`int </api_ru/.types/int>`

  Example: FILES_AND_DIRECTORIES, FILES_ONLY or DIRECTORIES_ONLY

 .. php:attr:: dragEnabled

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: fileHiding

  :doc:`bool </api_ru/.types/bool>`

 .. php:attr:: controlButtonVisible

  :doc:`bool </api_ru/.types/bool>`



**Methods**

----------

 .. php:method:: showDialog($approveButtonText, $parent = null)

  :param $approveButtonText: 
  :param $parent: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: showSaveDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: showOpenDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api_ru/php/swing/UIWindow>` 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: addChoosableFilter($filter, $description)

  :param $filter: :doc:`callable </api_ru/.types/callable>` (File $file) -> bool
  :param $description: 

 .. php:method:: addChoosableExtensions($extensions, $description, $showDirectories = true)

  :param $extensions: :doc:`array </api_ru/.types/array>` ['jpg', 'gif', 'png', ... etc]
  :param $description: 
  :param $showDirectories: 

 .. php:method:: resetChoosableFilters()


 .. php:method:: isTraversable($file)

  :param $file: 
  :returns: :doc:`bool </api_ru/.types/bool>` 

 .. php:method:: ensureFileIsVisible($file)

  :param $file: 

 .. php:method:: approveSelection()


 .. php:method:: cancelSelection()


 .. php:method:: changeToParentDirectory()




.. include:: /api_ru.desc/php/swing/UIFileChooser.footer.rst

