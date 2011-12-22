Toggle Airport
==============

This little utility will detect the presence of an ethernet connection, and
will turn the AirPort wifi connection on or off accordingly.

* If you're on wifi and you plug in an ethernet cable, it will turn off the wifi.
* If you're connected to an ethernet cable and you un plug it, it will turn the wifi on.

Install
-------

I have always run this with the files in the following locations.
I think it may be possible to put the files in your user Library,
but I haven't tested that.

/Library/Scripts/toggleAirport.sh
/System/Library/LaunchAgents/com.kevwil.toggleairport.plist

TODO
----

* determine if this works if only user file locations are used
* create installer - script? mac pkg?
* figure out what I did with that missing 'statusChanged.sh' script

License
-------

This is released under the MIT/X11 license. Copyright 2011 Kevin D. Williams

