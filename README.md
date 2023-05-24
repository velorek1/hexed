# HexEditor
Hex Editor GUI demo
NOTE: FOR X11 headers in linux.

TO COMPILE:  

    * Install Freepascal. Download or clone repository.
    * Install X11 headers: sudo apt-get install xorg-dev
    * Type "fpc hexeditor.pas" to build.

GUI with menus, windows, scroll list with mouse and keyboard interface.

The program uses PtcGraph, PtcCrt, PtcMouse included in FreePascal 2.6 or higher for Graphics. 


Units:
======

Graph mode:

* gfxn.pas >> Graphic Unit to add buttons, textbox.
* gfwin.pas >> Graphic Unit to create windows.
* hex2bin.pas >> Unit to handle different operations with hexadecimals.
* gaedch2.pas >> Buttons, dyanmic linked list for selection
* opendunit.pas >> Unit for the Openfile dialog

Programs:
=========
* hexeditor.pas >> Main program (demo).

![Alt text](hexed.png?raw=true "HexEditor")

EOF
