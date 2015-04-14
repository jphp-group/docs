UIElement
-------------------

.. include:: /api_en.desc/php/swing/UIElement.header.rst

.. php:class:: php\\swing\\UIElement

 **abstract** class

**Children**

----------------------

 * **abstract** **class** :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`



**Properties**

----------

 .. php:attr:: uid

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: group

  :doc:`string </api_en/.types/string>`

 .. php:attr:: x

  :doc:`int </api_en/.types/int>`

  Position X

 .. php:attr:: y

  :doc:`int </api_en/.types/int>`

  Position Y

 .. php:attr:: w

  :doc:`int </api_en/.types/int>`

  Width

 .. php:attr:: h

  :doc:`int </api_en/.types/int>`

  Height

 .. php:attr:: size

  :doc:`array </api_en/.types/array>`

  Size (width and height), [int, int]

 .. php:attr:: preferredSize

  :doc:`php\\swing\\array [int, int] </api_en/php/swing/array [int, int]>`

 .. php:attr:: minSize

  :doc:`array </api_en/.types/array>`

  Min Size (width and height) [int, int]

 .. php:attr:: autosize

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: position

  :doc:`array </api_en/.types/array>`

  Position (x and y), [int, int]

 .. php:attr:: screenPosition

  :doc:`array </api_en/.types/array>`

  Screen Position (x and y), [int, int]

 .. php:attr:: absolutePosition

  :doc:`array </api_en/.types/array>`

  **read-only**


  Absolute Position (x and y), [int, int]

 .. php:attr:: visible

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: enabled

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: focusable

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: align

  :doc:`php\\swing\\string - NONE, LEFT, RIGHT, TOP, BOTTOM, CLIENT </api_en/php/swing/string - NONE, LEFT, RIGHT, TOP, BOTTOM, CLIENT>`

 .. php:attr:: anchors

  :doc:`array </api_en/.types/array>`

  [LEFT, TOP, RIGHT, BOTTOM]

 .. php:attr:: font

  :doc:`php\\swing\\Font </api_en/php/swing/Font>`

 .. php:attr:: border

  :doc:`php\\swing\\Border </api_en/php/swing/Border>`

 .. php:attr:: background

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: foreground

  :doc:`php\\swing\\Color </api_en/php/swing/Color>`

 .. php:attr:: tooltipText

  :doc:`string </api_en/.types/string>`

 .. php:attr:: doubleBuffered

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: opaque

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: ignoreRepaint

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: autoscrolls

  :doc:`bool </api_en/.types/bool>`

 .. php:attr:: uiClassId

  :doc:`string </api_en/.types/string>`

  **read-only**


 .. php:attr:: popupMenu

  :doc:`php\\swing\\UIPopupMenu </api_en/php/swing/UIPopupMenu>`

 .. php:attr:: cursor

  :doc:`string </api_en/.types/string>`

 .. php:attr:: padding

  :doc:`php\\swing\\array [int, int, int, int] </api_en/php/swing/array [int, int, int, int]>`

 .. php:attr:: owner

  :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`

 .. php:attr:: parent

  :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`

 .. php:attr:: firstParent

  :doc:`php\\swing\\UIContainer </api_en/php/swing/UIContainer>`



**Methods**

----------

 .. php:method:: __construct()


 .. php:method:: getGraphics()

  Get graphic canvas object

  :returns: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

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

  :param $name:  - - name of event
  :param $callback: :doc:`callable </api_en/.types/callable>` 
  :param $group: :doc:`string </api_en/.types/string>` 

 .. php:method:: off($name, $group = NULL)

  Remove all event callbacks (if group == null), or only group

  :param $name: 
  :param $group: :doc:`null </api_en/.types/null>`, :doc:`string </api_en/.types/string>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: trigger($name)

  Trigger callback by event name

  :param $name: 

 .. php:method:: addAllowedEventType($name)

  **protected**


  :param $name: :doc:`string </api_en/.types/string>` 

 .. php:method:: setAction($name, $callback = null)

  :param $name: :doc:`string </api_en/.types/string>` 
  :param $callback: :doc:`callable </api_en/.types/callable>` 

 .. php:method:: setInputKey($keyString, $actionName)

  :param $keyString: :doc:`string </api_en/.types/string>` 
  :param $actionName: :doc:`string </api_en/.types/string>` 

 .. php:method:: hasFocus()

  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: add($component, $index = null)

  Add child component

  :param $component: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 
  :param $index: :doc:`null </api_en/.types/null>`, :doc:`int </api_en/.types/int>` 

 .. php:method:: getComponentAt($x, $y)

  Determines if this component or one of its immediate
  subcomponents contains the (x, y) location,
  and if so, returns the containing component. This method only
  looks one level deep.

  :param $x: 
  :param $y: 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 

 .. php:method:: printOne($canvas)

  Prints this component.

  :param $canvas: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: printAll($canvas)

  Prints this component and all of its subcomponents.

  :param $canvas: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: paintOne($canvas)

  Paints this component.

  :param $canvas: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: paintAll($canvas)

  Paints this component and all of its subcomponents.

  :param $canvas: :doc:`php\\swing\\Graphics </api_en/php/swing/Graphics>` 

 .. php:method:: updateUI()


 .. php:method:: invalidate()


 .. php:method:: repaint()


 .. php:method:: revalidate()


 .. php:method:: repaintRegion($x, $y, $w, $h)

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 
  :param $w: :doc:`int </api_en/.types/int>` 
  :param $h: :doc:`int </api_en/.types/int>` 

 .. php:method:: grabFocus()


 .. php:method:: getTextWidth($str)

  Return width of str for drawText + current font

  :param $str: 
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getTextHeight()

  Return height of one line text with current font

  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: show()


 .. php:method:: hide()


 .. php:method:: toggle()


 .. php:method:: removeSelf()


 .. php:staticmethod:: getByUid($uid)

  Get component by unique id

  :param $uid: :doc:`string </api_en/.types/string>` 
  :returns: :doc:`php\\swing\\UIElement </api_en/php/swing/UIElement>` 



.. include:: /api_en.desc/php/swing/UIElement.footer.rst

