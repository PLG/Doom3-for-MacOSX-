# Doom3-for-MacOSX

This is a fork of Kostas "Bad Sector" Michalopoulos's *"Doom3-for-MacOSX"*,<br/>
which is a fork of Fabien Sanglard's *"Build Doom3 on MacOSX with XCode4"*.</br>
http://fabiensanglard.net/doom3_macosx/index.php

## Kostas "Bad Sector" Michalopoulos

This is a fork of fabiensanglard's Doom 3 for Mac OSX ...fork :-P

It is modified to build properly under the latest Xcode and Mac OSX.

Currently there are some bugs (UI transition has been disabled because of a
linking issue with the templates - shouldn't be hard to fix, i just need some
time - and fullscreen modes are not support - again not hard, but...), but the
game is fully playable and performs fine under a late 2009 iMac with 9400M in
1024x768 with Ultra quality mode (it just takes a bit to load the textures, so
High or Medium quality should be better to avoid pauses).

## Fabien Sanglard

This is a release that will compile in "one click" on Mac OS X Intel with XCode.

After building you will need to:
 
 - copy `game.dylib` to `/usr/local/lib` (or create a symbolic link). 
 - add the base folder containing the game assets.

For more informations, check http://fabiensanglard.net/doom3_macosx/index.php

Happy hacking :) !

Fabien
