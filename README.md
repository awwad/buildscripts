buildscripts
============

Build Seattle Testbed components from source code available on Github.  Built components may be executed
and tested.

The `initialize.py` and `build.py` scripts are redistributed with every buildable Seattle Testbed repository
and a "master copy" of each script (and thus the most up-to-date version) is kept here.  `initialize.py` does
a `git clone` of all the dependent repositories of a Seattle Testbed component.  `build.py` generates
runnable components out of source code that has been checked out.

[Insructions](https://seattle.poly.edu/wiki/BuildInstructions) are available that cover every step of the
Seattle Testbed build process and explain how these build scripts work.
