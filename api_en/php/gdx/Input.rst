Input
-------------

.. include:: /api_en.desc/php/gdx/Input.header.rst

.. php:class:: php\\gdx\\Input

 **final** class




**Methods**

----------

 .. php:method:: __construct()

  **private**



 .. php:method:: getAccelerometerX()

  :returns: :doc:`double </api_en/.types/double>` The value of the accelerometer on its x-axis. ranges between [-10,10].

 .. php:method:: getAccelerometerY()

  :returns: :doc:`double </api_en/.types/double>` The value of the accelerometer on its y-axis. ranges between [-10,10].

 .. php:method:: getAccelerometerZ()

  :returns: :doc:`double </api_en/.types/double>` The value of the accelerometer on its y-axis. ranges between [-10,10].

 .. php:method:: getX($pointer)

  Returns the x coordinate of the last touch on touch screen devices and the current mouse position on desktop for the first
  pointer in screen coordinates. The screen origin is the top left corner.

  :param $pointer: :doc:`int </api_en/.types/int>`  - (optional) the pointer id. Returns the x coordinate in screen coordinates of the given pointer.
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDeltaX($pointer)

  :param $pointer: :doc:`int </api_en/.types/int>`  - (optional) the pointer id.
  :returns: :doc:`int </api_en/.types/int>` the different between the current pointer location and the last pointer location on the x-axis.

 .. php:method:: getY($pointer)

  Returns the y coordinate of the last touch on touch screen devices and the current mouse position on desktop for the first
  pointer in screen coordinates. The screen origin is the top left corner.

  :param $pointer: :doc:`int </api_en/.types/int>`  - (optional) the pointer id. Returns the y coordinate in screen coordinates of the given pointer.
  :returns: :doc:`int </api_en/.types/int>` 

 .. php:method:: getDeltaY($pointer)

  :param $pointer: :doc:`int </api_en/.types/int>`  - (optional) the pointer id.
  :returns: :doc:`int </api_en/.types/int>` the different between the current pointer location and the last pointer location on the y-axis.

 .. php:method:: isTouched($pointer)

  :param $pointer: :doc:`int </api_en/.types/int>`  - (optional)
  :returns: :doc:`bool </api_en/.types/bool>` whether the screen is currently touched.

 .. php:method:: justTouched()

  :returns: :doc:`bool </api_en/.types/bool>` whether a new touch down event just occurred.

 .. php:method:: isButtonPressed($button)

  Whether a given button is pressed or not. Button constants can be found in {@link Buttons}. On Android only the Button#LEFT
  constant is meaningful.

  :param $button: :doc:`int </api_en/.types/int>` 
  :returns: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: isKeyPressed($key)

  Returns whether the key is pressed.

  :param $key: :doc:`int </api_en/.types/int>` 

 .. php:method:: setOnscreenKeyboardVisible($visible)

  Sets the on-screen keyboard visible if available.

  :param $visible: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: vibrate($millis)

  Vibrates for the given amount of time. Note that you'll need the permission
  <code> <uses-permission android:name="android.permission.VIBRATE" /></code> in your manifest file in order for this to work.

  :param $millis: :doc:`int </api_en/.types/int>`  - the number of milliseconds to vibrate.

 .. php:method:: cancelVibrate()


 .. php:method:: getAzimuth()

  The azimuth is the angle of the device's orientation around the z-axis. The positive z-axis points towards the earths
  center.

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: getPitch()

  The pitch is the angle of the device's orientation around the x-axis. The positive x-axis roughly points to the west and is
  orthogonal to the z- and y-axis.

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: getRoll()

  The roll is the angle of the device's orientation around the y-axis. The positive y-axis points to the magnetic north pole
  of the earth.

  :returns: :doc:`double </api_en/.types/double>` 

 .. php:method:: getCurrentEventTime()

  :returns: :doc:`int </api_en/.types/int>` the time of the event currently reported to the InputProcessor.

 .. php:method:: setCatchBackKey($catchBack)

  Sets whether the BACK button on Android should be caught. This will prevent the app from being paused. Will have no effect
  on the desktop.

  :param $catchBack: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: setCatchMenuKey($catchMenu)

  Sets whether the MENU button on Android should be caught. This will prevent the onscreen keyboard to show up. Will have no
  effect on the desktop.

  :param $catchMenu: :doc:`bool </api_en/.types/bool>` 

 .. php:method:: getRotation()

  :returns: :doc:`int </api_en/.types/int>` the rotation of the device with respect to its native orientation.

 .. php:method:: getNativeOrientation()

  :returns: :doc:`string </api_en/.types/string>` the native orientation of the device.

 .. php:method:: setCursorCatched($catched)

  Only viable on the desktop. Will confine the mouse cursor location to the window and hide the mouse cursor.

  :param $catched: :doc:`bool </api_en/.types/bool>`  - whether to catch or not to catch the mouse cursor

 .. php:method:: isCursorCatched()

  :returns: :doc:`bool </api_en/.types/bool>` whether the mouse cursor is catched.

 .. php:method:: setCursorPosition($x, $y)

  Only viable on the desktop. Will set the mouse cursor location to the given window coordinates (origin top-left corner).

  :param $x: :doc:`int </api_en/.types/int>` 
  :param $y: :doc:`int </api_en/.types/int>` 

 .. php:method:: setCursorImage($pixmap, $xHotspot, $yHotspot)

  Only viable on the desktop. Will set the mouse cursor image to the image represented by the
  Pixmap. The Pixmap must be in RGBA8888 format, width & height must be powers-of-two
  greater than zero (not necessarily equal), and alpha transparency must be single-bit (i.e., 0x00 or 0xFF only). To revert to
  the default operating system cursor, pass in a null Pixmap; xHotspot & yHotspot are ignored in this case.

  :param $pixmap: :doc:`php\\gdx\\graphics\\Pixmap </api_en/php/gdx/graphics/Pixmap>` 
  :param $xHotspot: :doc:`int </api_en/.types/int>` 
  :param $yHotspot: :doc:`int </api_en/.types/int>` 



.. include:: /api_en.desc/php/gdx/Input.footer.rst

