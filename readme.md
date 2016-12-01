XDebug Helper for Nette Framework
=================================
Copyright (c) 2010-2013 Jan 'Panda' Smitka


Simple extension for Nette Framework, which integrates into the Debug Bar and
enables you to easily start and stop a Xdebug session.


Requirements
------------

* Nette Framework 2.3
* PHP 5.6 or greater

If you wish to run this extension on PHP 5.2, just remove the namespace and
use block in XDebugHelper.php.


Usage
-----

Simply register a new debug panel in your config.neon:

	tracy:
		bar:
			- NetteExtras\XDebugHelper

You can optionally specify your IDE key as the first parameter of
the XDebugHelper constructor. Defaults to netbeans-xdebug, which is the most
suitable option for NetBeans users.
