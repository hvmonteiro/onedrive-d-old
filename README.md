onedrive-d
==================

Description
-----------
This project intends to develop a OneDrive (formerly SkyDrive) daemon on (X)ubuntu with mainly Bash script.
The server-client interaction is based on python-skydrive (https://github.com/mk-fg/python-skydrive) by Mike Kazantsev.

Installation
--------------
Execute the command: `sudo ./setup.sh` to install the daemon.


File Description
------------------

`setup.sh`:
    The installation script. Sudo permission required.

`inst_pre_requisites.sh`:
	The script to install python-skydrive and its pre-requisite packages

`onedrive-d`:
	The daemon itself

`synchronize.py`:
	The synchronizer

`entries.py`:
	Class definitions for file and directory entries

Homepage
-----------
Please visit: http://www.xybu.me/projects/skydrive-d/


Contact
--------

Xiangyu Bu
