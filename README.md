FreeRDP: A Remote Desktop Protocol Implementation
=================================================

FreeRDP is a free implementation of the Remote Desktop Protocol (RDP), released under the Apache license.
Enjoy the freedom of using your software wherever you want, the way you want it, in a world where
interoperability can finally liberate your computing experience.

Resources
---------

Project website: http://www.freerdp.com/

Issue tracker: https://github.com/FreeRDP/FreeRDP/issues

Sources: https://github.com/FreeRDP/FreeRDP/
Downloads: https://pub.freerdp.com/releases/
Wiki: https://github.com/FreeRDP/FreeRDP/wiki
API documentation: https://pub.freerdp.com/api/


IRC channel: #freerdp @ irc.freenode.net

Mailing list: https://lists.sourceforge.net/lists/listinfo/freerdp-devel


Microsoft Open Specifications
-----------------------------

Information regarding the Microsoft Open Specifications can be found at:

http://www.microsoft.com/openspecifications/

A list of reference documentation is maintained here:

https://github.com/FreeRDP/FreeRDP/wiki/Reference-Documentation


Compilation
-----------

Instructions on how to get started compiling FreeRDP can be found on the wiki:

https://github.com/FreeRDP/FreeRDP/wiki/Compilation

Simple version:
`sudo apt-get install build-essential git-core cmake xsltproc libssl-dev libx11-dev libxext-dev libxinerama-dev   libxcursor-dev libxdamage-dev libxv-dev libxkbfile-dev libasound2-dev libcups2-dev libxml2 libxml2-dev   libxrandr-dev libgstreamer0.10-dev libgstreamer-plugins-base0.10-dev libxi-dev libgstreamer-plugins-base1.0-dev libavutil-dev libavcodec-dev`

`git clone git@gitlab.ais:davisb/FreeRDP.git`

`mkdir FreeRDP--`

`cd FreeRDP--`

`cmake ../FreeRDP/`

`make`

`sudo make install`
