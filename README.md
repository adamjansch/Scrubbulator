Scrubbulator
============

**Scrubbulator** is an audio instrument designed by Adam Jansch, built in Max/MSP, for laptop performance with the laptop ensemble <a href="http://www.helopg.co.uk" title="HELOpg" target="_blank">HELOpg</a>. Scrubbulator mimics the effect of 'scrubbing' – a technique used with reel-to-reel tape machines to precisely locate points in the tape for editing.

Playing Scrubbulator is simple: load an audio file, and click on the waveform to loop a short segment at the playhead. The vertical position of the mouse pointer in the waveform determines the duration of the looped section. Releasing the mouse button stops the loop, or looping make be latched on by pressing the 'L' key.

Some additional functionality can be accessed over OSC: output pan and EQ are controllable through specific OSC parameter names. This was designed with <a href="http://hexler.net/software/touchosc" title="TouchOSC" target="_blank">TouchOSC</a> in mind.

<div id="intro-end"></div>

Installation
------------

1. Move Scrubbulator files into a directory in your Max/MSP search path.
2. Install Peter Elsea's <a href="http://artsites.ucsc.edu/EMS/music/research/Lobjects.readme.html" title="LObjects" target="_blank">LObjects</a> and CNMAT's <a href="http://cnmat.berkeley.edu/downloads" title="OpenSoundControl and OSC-route" target="_blank">OpenSoundControl and OSC-route</a> third party externals.
3. Open Scrubbulator and start scrubbulating.


Usage
-----

1. Switch on DSP, located in the top-right corner.
2. Drag an audio file to the load dropper. Any format supported by Quicktime may be loaded.
3. Click on waveform to start scrubbulating.


Other controls
--------------

* Maximum loop length number box: duration in milliseconds when mouse pointer is at the bottom of the waveform 
* Spacebar: play audio file normally from last clicked position
* L: latch looping on/off
* Ctrl: Zoom waveform in/out (with mouse up/down)
* Shift: lock horizontal axis
* Alt: lock vertical axis
