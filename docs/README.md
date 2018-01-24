All available commands are described below. If you need more details, run `pem help` or `pem <command> help` to get them.

help
----
Displays a help message.

python-install
--------------
Installs desired version of Python. In addition, the command updates `pip` to the latest version and installs `virtualenv` package.

@todo #58 Rename `python-install` to `install` as we can install only Python.

@todo #58 Add ability to install several versions at the same time.

python-default
--------------
Configures provided Python's environment as default for the system.

@todo #58 Rename `python-default` to `default`.

python-remove
-------------
Removes provided Python's environment.

@todo #58 Rename `python-remove` to `remove`.

@todo #58 Add ability to remove several versions at the same time.

folder-clean
------------
Removes Python's environment which was configured for this directory.

@todo #58 Rename `folder-clean` to `clean-dir-env`.

folder-env
----------
Creates an environment for a current directory. Also, the command configures created environment as a local one for the directory.

@todo #58 Rename `folder-env` to `create-dir-env`.

@todo #58 Update `create-dir-env` command implementation if it doesn't match with the documentation.


folder-state
-------------
Displays Python's path which was configured for the directory. If the environment is absent, a default Python's path will be displayed.

@todo #58 Rename `folder-state` to `current-env`. Make sure the current implementation matches with this documentation.

create-float-env
----------------
Creates a float environment. In order to use it, you have to `activate` it.

@todo #58 Implement `create-float-env` command

activate
--------
Activates an environment.

@todo #58 Implement `activate` command