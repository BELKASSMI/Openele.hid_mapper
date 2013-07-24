Openele.hid_mapper
==================
Author :
========
BELKASSMI Moussa
Version :
=========
beta
Description  :
==============
HID devices used to send commands to the X server. However all commands  received are not always directly usable on  Linux. This is why it is interesting to be able to "remap”  them to linux commands (inputdev) of our choice.
HID mapper is a generic driver developed basically for linux ,  which can convert any HID signal to a key event that can easily be used in XBMC. The Openelec_HID_mapper  project is an adaptation of hid_mapper for OpenELEC  distribution. The work consisted of cross-compiling the driver  to be installable in OpenELEC.  Source files for compilation as well as the procedure of compilation, installation and user guide are given for all intents and purposes.
Compilation:
============
to create the add-on follow this instructions:
Start by updating your system (on Ubuntu or other Debian-based distribution): check here: http://wiki.openelec.tv/index.php?title=Compile_from_source , untul you download Openelec.tv from github .
Now put the directory hid_mapper from this project  in /home/user/Openelec.tv/addons/debug .
To compile the add-on use this command: 
   cd Openelec.tv
	PROJECT=project ARCH=architecture    ./scripts/create_addon     hid_mapper
Examples:
=========
	PROJECT=FUSION    ARCH=x86_64     ./scripts/create_addon     hid_mapper


The add-on will be found in this path  /home/user/Openelec.tv/target/addons/

Installation  :
===============
the zip file now will be installed vi the XBMC add-on manager see from below :
Go to part tree how to install from a zip file : http://wiki.xbmc.org/index.php?title=Add-on_manager
Contributors :
==============
License : Copyright 2013
