araiwm - arai window manager
----------------------------
manages windows (and a config file!) no da

Requirements
------------
XCB header files

Configuration
-------------
araiwm-config is configured by editing an araiwm.conf file and restarting
an example araiwm.conf is provided in the repository

Installation
------------
install using

	make install clean

Launching araiwm
----------------
araiwm takes either no args, or the path to a config file
if no config is provided, araiwm will use kaiser's defaults

Display Managers
----------------
edit the dm/startarai script with programs you want to run along araiwm, like a hotkey manager, for example, then install using
	
	make install_dm clean

Todo
----
nothing!
