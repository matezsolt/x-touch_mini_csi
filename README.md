# Behringer X-Touch Mini Reaper CSI Template

## Things You need
* [Cockos Reaper](https://www.reaper.fm/)
* [Control Surface Integrator - CSI Reaper Plugin](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki)
* [Behringer X-Touch Mini](https://www.behringer.com/product.html?modelCode=P0B3M) control surface

## Installation
1. Install Reaper
2. Install CSI, [see documentation](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Installation)
3. Put CSI folder and it's files into the Reaper Resource Path\CSI folder keeping the structure. If you're already running  CSI and currently have a working configuration, do NOT overwrite your current CSI.ini with the one provided. The Midi surface configuration should be 
* 8 Number of Channels, 
* 0 Channel Start position, 
* 8 Number of Sends, 
* 8 Number os FX Menu, 
* Surface: XTouchMini_MC_MODE.mst, 
* Zone Folder: XTouchMini_MC_MODE.
4. Do not forget to disable X-TOUCH MINI In/Out MIDI ports in Reaper > Option > Preferences > MIDI devices
5. X-Touch Mini needs to be in MC mode (MC MODE LED is lit). You can change from normal mode with powering up and holding down MC button, until the LEDs flash.

Enjoy!
