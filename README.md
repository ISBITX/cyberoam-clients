Graphical Cyberoam Client
========================

About
------
A graphical cyberoam client build using PyQt primarily because of the lack of an official GUI client for Linux.
And yes this will run on both Windows and Linux :)

I have tested it on Ubuntu 12.04 x64 (KDE and Unity), and Windows 7 x64

Installation and Usage
----------------------
The client requires the following software to be installed:
* python 2.7 (http://www.python.org/getit)
* pyqt4 (http://www.riverbankcomputing.co.uk/software/pyqt/download/)

Ubuntu users can install it by running `apt-get install python python-qt4`

To use, just run `python cyberoam.py`

Limitations
-----------
* Needs a terminal tab open for it to be running (see workaround below).
* Have not really worked on the layout. It needs refining. Volunteers anyone?

Workaround:
You can use the provided scripts to open cyberoam client outside the terminal/cmd. Just edit the paths inside the scripts.
Also you'll need to make the linux script executable: `chmod +x cyberoam`

I may create a proper installer sometime :)

License
-------
GPLv3

