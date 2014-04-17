php\\lang\\Module
-----------------

.. contents::
   :depth: 3

API
>>>

.. php:class:: php\\lang\\Module

	Class for loading php modules from files and streams.

	.. php:method:: __construct($source, $compiled = false, $debugInformation = true)

		Loads a module from a source, registers all classes and functions of the loaded module

		:param php\\io\\Stream or php\\io\\File or string $source: source of module
		:param bool $compiled: compiled to bytecode
		:param bool $debugInformation: load and save debug infomration (source lines, positions, etc)

	.. php:method:: call($variables = null)

		Includes the module, execute all scripts outside functions and classes.

		:param array $variables: global variables that passing into the module
		:returns: mixed - the result of including script

	.. php:method:: dump($target, $saveDebugInformation = true)

		Dumps the module to bytecode

		:param php\\io\\Stream or php\\io\\File or string $target: where to save the result of dumping
		:param bool $saveDebugInformation: enable/disable to add debug information to the result