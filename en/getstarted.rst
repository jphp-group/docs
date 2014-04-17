Getting Started
===============

.. contents::
   :depth: 2
   :backlinks: top

Building from sources
>>>>>>>>>>>>>>>>>>>>>

To build JPHP you need to:


#. Install JDK (OpenJDK or Oracle) for your OS.
	
	.. note::
		* For Window's users: `<http://www.oracle.com/technetwork/java/javase/downloads/index.html>`_
		* For Linux's users: `<http://openjdk.java.net/install/index.html>`_
 
#. Install the Gradle system for building sources `<http://gradle.org/>`_

	.. note::
		Do not forget to add the gradle bin path to your PATH variable

#. Get the all sources from our `reposiroty <https://github.com/jphp-compiler/jphp.git>`_ ::

	git clone https://github.com/jphp-compiler/jphp.git
	cd jphp

#. Build jar files via Gradle::

	gradle jar

Now you can find an executable jar file in the ``jphp-cli/build/libs`` directory. To check that all is success, use the
following command::

	cd jphp-cli/build/libs
	chmod +x jphp # for linux
	./jphp -v # show version

Using with Maven
>>>>>>>>>>>>>>>>
.. code-block:: xml
	
	<dependency>
	    <groupId>org.develnext</groupId>
	    <artifactId>jphp-core</artifactId>
	    <version>0.4-SNAPSHOT</version>
	</dependency>

And add our maven repository:

.. code-block:: xml

	<repository>
	    <id>DevelNext Repo</id>
	    <url>http://maven.develnext.org/repository/snapshots/</url>
	</repository>

You can also try our extensions for jphp (only change ``artifactId`` to the next values): 

#. ``jphp-zend-ext`` - Extension for backward capability with Zend PHP
#. ``jphp-json-ext`` - JSON extension
#. ``jphp-cli`` - for using JPHP via CLI
#. ``jphp-swing-ext`` - GUI extension based on Swing.

Create executable JAR
>>>>>>>>>>>>>>>>>>>>>

Use the ``php.runtime.launch.Launcher`` class as the Main class for your jar. By default, the launcher loads the ``JPHP-INF/launcher.conf`` configuration from a resource directory, inside this file you can specify the name of the bootstrap php file (which will be loaded from a resource directory and executed)::

	bootstrap.file = bootstrap.php

We created an example project which is located in the ``jphp-example-project`` directory. To try it, you should use the Gradle build system and several tasks: ``exampleStart`` or ``jar`` to build the project to a jar file which you can execute by using Java VM. By default, all jar files will be created in ``build/libs/``.


Testing
>>>>>>>

To run the tests of JPHP you can use the next command::

	cd /path/to/jphp/sources/
	gradle check