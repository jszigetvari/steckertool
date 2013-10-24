steckertool
===========

A console-based management utility for the IPStecker product line of Procontrol Electronics Ltd.
Works on Linux, but uses many forms of bashism, thus needs bash (and some other common utilities) to work properly.

IPStecker is an IP-managed power socket family produced by the Hungarian company Procontrol Electronics Ltd.
The product can be purchased at: http://www.procontrol.hu

The creator of this utility is not affiliated with the company in any way.

Usage examples
==============

steckertool -H HOSTNAME -p PASSWORD query
steckertool -h
steckertool switchon name server
steckertool switchoff 1-3
steckertool flip 1,3-4
steckertool switchon 1,2,3,4
steckertool flip 2
steckertool -H HOSTNAME -p PASSWORD switchon all

Downloads
=========

The files for this project may be downloaded from http://github.com/jszigetvari/steckertool or the files may be
cloned from git, using the following command:
git clone http://github.com/jszigetvari/steckertool

