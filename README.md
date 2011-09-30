Scrubbulator
============

**Scrubbulator** is an audio instrument designed by Adam Jansch, built in Max/MSP, for laptop performance with the laptop ensemble [HELOpg](http://www.helopg.co.uk). Scrubbulator mimics the effect of 'scrubbing' – listening to an audio file whilst fast-forwarding or rewinding, but with some extra features thrown in.

Playing Scrubbulator is simple: load in an audio file, then click on the waveform to loop a short segment at the playhead. The vertical position of the mouse pointer in the waveform determines the duration of the looped section. Releasing the mouse button stops the loop, through there is also a latching function, enabled by pressing the 'L' key.

Some additional functionality can be accessed over OSC: output pan and EQ are controllable through specific OSC parameter names. This was designed with [TouchOSC](http://hexler.net/software/touchosc) in mind.


Installation
------------

1. Move Scrubbulator files into a directory in your Max/MSP search path.
2. Install Peter Elsea's [LObjects](http://artsites.ucsc.edu/EMS/music/research/Lobjects.readme.html) and CNMAT's [OpenSoundControl and OSC-route](http://cnmat.berkeley.edu/downloads) third party externals.
3. Open Scrubbulator and start scrubbulating.


Usage
-----

1. Switch on DSP, located in the top-right corner.
2. Drag an audio file to the load dropper. Any format supported by Quicktime may be loaded.
3. Click on waveform to start scrubbulating.


Other controls
--------------

Maximum loop length number box: duration in milliseconds when mouse pointer is at the bottom of the waveform 
Spacebar: play audio file normally from last clicked position
L: latch looping on/off
Ctrl: Zoom waveform in/out (with mouse up/down)
Shift: lock horizontal axis
Alt: lock vertical axis
