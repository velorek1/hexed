# colorpicker
True Color Picker GUI demo
NOTE: FOR X11 headers in linux.

TO COMPILE:  

    * Install Freepascal. Download or clone repository.
    * Install X11 headers: sudo apt-get install xorg-dev
    * Type "fpc colpick.pas" to build.

Chose from 16,777,216 colors (TRUE COLOR 24-bit) with a GUI with menus, windows, scroll list with mouse and keyboard interface.

My units use PtcGraph, PtcCrt, PtcMouse included in FreePascal 2.6 or higher for Graphics. 


I've created this only for fun and to learn programming. That's why they are full of mistakes and redundancies.
I hope this will help me become a better programmer one day. 

Units:
======

Graph mode:

* gfxn.pas >> Graphic Unit to add buttons, textbox.
* gfwin.pas >> Graphic Unit to create windows.
* hex2bin.pas >> Unit to handle different operations with hexadecimals.

Programs:
=========
* colpick.pas >> True Color palette picker.

![Alt text](cpick.png?raw=true "Color picker")

EOF
