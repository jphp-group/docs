.. include:: /sdk/php/lang/Module.rst

About
>>>>>>>>>>>>

In PHP you should use the ``include`` or ``require`` functions to include scripts, but JPHP has more
powerful approach to do this.

.. note::

	JPHP also supports the ``include``, ``include_once``, ``require`` and ``require_once`` functions but
	we do not recomend you to use these functions. Instead of this you can use the Module class + `autoloading classes`.   

Include file
>>>>>>>>>>>>

For example we have some script file named as `script.php` and located at `path/to/`. We need to
include this file. 

We have the ``path/to/script.php`` file:

.. code-block:: php

	static $i = 0;
	$i++;
	return "success #$i";


And at the next step we include this file by using the Module class:

.. code-block:: php

	use php\lang\Module;

	$module = new Module('path/to/script.php');
	echo $module->call(), "\n";
	echo $module->call(), "\n";

Output will be::

	success #1
	success #2

Dump module to bytecode
>>>>>>>>>>>>>>>>>>>>>>>

To dump a loaded module (script) to bytecode, you should use the :php:meth:`dump` method. Why do you need it? 
A compiled module (script) is loaded faster and doesn't contain original php code. 

.. code-block:: php

	use php\lang\Module;
	$module = new Module('path/to/script.php');
	$module->dump('path/to/script.php.compiled');

	// load the compiled script
	$module = new Module('path/to/script.php.compiled', true);
	echo $module->call();

Output will be::

	success #1


Classes and Functions in module
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

A module may contain some classes and functions, they will be automatically registered when an instance of 
the Module class will be created. For example:

We have the ``script.php`` file:

.. code-block:: php

	class Foo {
		function bar() {
			echo 'success';
		}
	}

	echo 'fail';

Now we load this file via the Module class:

.. code-block:: php

	use php\lang\Module;

	$module = new Module('script.php');
	echo Foo::bar();

Output::

	success


As you see, the ``fail`` string is not printed, it's normal behaviour for JPHP. If you want to output ``fail``, use
:php:meth:`call` method.