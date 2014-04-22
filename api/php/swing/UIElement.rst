UIElement
-------------------

.. php:class:: php\\swing\\UIElement

 **abstract** class


 .. php:method:: getGraphics()


  Get graphic canvas object

  :returns: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: on($name, $callback, $group = 'general')


  Events -
  Mouse:
  click
  mousePress
  mouseRelease
  mouseEnter
  mouseExit
  mouseMove
  mouseDrag
  Keyboard:
  keyDown
  keyUp
  keyPress
  Focus:
  focus
  blur
  Add callback for event

  :param $name: - name of event
  :param $callback: :doc:`callable </api/callable>` 
  :param $group: 

 .. php:method:: off($name, $group = NULL)


  Remove all event callbacks (if group == null), or only group

  :param $name: 
  :param $group: 
  :returns: :doc:`bool </api/bool>` 

 .. php:method:: trigger($name)


  Trigger callback by event name

  :param $name: 

 .. php:method:: hasFocus()

  :returns: :doc:`bool </api/bool>` 

 .. php:method:: add($component, $index = null)


  Add child component

  :param $component: :doc:`php\\swing\\UIElement </api/php/swing/UIElement>` 
  :param $index: 

 .. php:method:: getComponentAt($x, $y)


  Determines if this component or one of its immediate
  subcomponents contains the (x, y) location,
  and if so, returns the containing component. This method only
  looks one level deep.

  :param $x: 
  :param $y: 
  :returns: :doc:`php\\swing\\UIElement </api/php/swing/UIElement>` 

 .. php:method:: printOne($canvas)


  Prints this component.

  :param $canvas: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: printAll($canvas)


  Prints this component and all of its subcomponents.

  :param $canvas: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: paintOne($canvas)


  Paints this component.

  :param $canvas: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: paintAll($canvas)


  Paints this component and all of its subcomponents.

  :param $canvas: :doc:`php\\swing\\Graphics </api/php/swing/Graphics>` 

 .. php:method:: updateUI()


 .. php:method:: invalidate()


 .. php:method:: repaint()


 .. php:method:: revalidate()


 .. php:method:: repaintRegion($x, $y, $w, $h)

  :param $x: 
  :param $y: 
  :param $w: 
  :param $h: 

 .. php:method:: grabFocus()


 .. php:staticmethod:: getByUid($uid)


  Get component by unique id

  :param $uid: 
  :returns: :doc:`php\\swing\\UIElement </api/php/swing/UIElement>` 

