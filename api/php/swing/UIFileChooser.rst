UIFileChooser
-----------------------

.. php:class:: php\\swing\\UIFileChooser

 **extends**: :doc:`php\\swing\\UIContainer </api/php/swing/UIContainer>`


 Class UIFileChooser

 .. php:method:: showDialog($approveButtonText, $parent = null)

  :param $approveButtonText: 
  :param $parent: :doc:`php\\swing\\UIWindow </api/php/swing/UIWindow>` 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: showSaveDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api/php/swing/UIWindow>` 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: showOpenDialog($parent = null)

  :param $parent: :doc:`php\\swing\\UIWindow </api/php/swing/UIWindow>` 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: addChoosableFilter($filter, $description)

  :param $filter: :doc:`callable </api/callable>`  (File $file) -> bool
  :param $description: 

 .. php:method:: addChoosableExtensions($extensions, $description, $showDirectories = true)

  :param $extensions: :doc:`array </api/array>`   ['jpg', 'gif', 'png', ... etc]
  :param $description: 
  :param $showDirectories: 

 .. php:method:: resetChoosableFilters()


 .. php:method:: isTraversable($file)

  :param $file: 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: ensureFileIsVisible($file)

  :param $file: 

 .. php:method:: approveSelection()


 .. php:method:: cancelSelection()


 .. php:method:: changeToParentDirectory()


