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

## Layout
### "Home" layout
 -| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Layer
 -| - | - | - | - | - | - | - | - | ----- | -----
Encoder | Track 1 Volume | Track 2 Volume | Track 3 Volume | Track 4 Volume | Track 5 Volume | Track 6 Volume | Track 7 Volume | Track 8 Volume | Master Track Volume | -
Encoder push | - | - | - | - | - | - | - | - | - | -
Button upper | Track 1 Solo | Track 2 Solo | Track 3 Solo | Track 4 Solo | Track 5 Solo | Track 6 Solo | Track 7 Solo | Track 8 Solo | - | Layer A/Control [-]
Button lower | Track Bank -8 | Track Bank +8 | Go to previous marker/project start | Go to next marker/project end | Cycle Timeline | Stop | Play | Record | - | Layer B/Shift [-]
Hold+Button lower | - | - | Go to start of project | Go to end of project | - | Toggle VCA Mode | - | - | - | -

### Shift+"Home" layout
 -| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Layer
 -| - | - | - | - | - | - | - | - | ----- | -----
Encoder | Track 1 Pan/Pan Width | Track 2 Pan/Pan Width | Track 3 Pan/Pan Width | Track 4 Pan/Pan Width | Track 5 Pan/Pan Width | Track 6 Pan/Pan Width | Track 7 Pan/Pan Width | Track 8 Pan/Pan Width | Master Track Volume | -
Encoder push | Encoder 1 Pan/Pan width | Encoder 2 Pan/Pan width | Encoder 3 Pan/Pan width | Encoder 4 Pan/Pan width | Encoder 5 Pan/Pan width | Encoder 6 Pan/Pan width | Encoder 7 Pan/Pan width | Encoder 8 Pan/Pan width | - | -
Button upper | Track 1 Mute | Track 2 Mute | Track 3 Mute | Track 4 Mute | Track 5 Mute | Track 6 Mute | Track 7 Mute | Track 8 Mute | - | Layer A/Control [-]
Button lower | Track Bank -8 | Track Bank +8 | Go to previous marker/project start | Go to next marker/project end | Cycle Timeline | Stop | Play | Record | - | Layer B/Shift [X]
Hold+Button lower | - | - | Go to start of project | Go to end of project | - | Toggle VCA Mode | - | - | - | -

### Control+"Home" layout
 -| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Layer
 -| - | - | - | - | - | - | - | - | ----- | -----
Encoder | Selected Track Send 1 volume | Selected Track Send 2 volume | Selected Track Send 3 volume | Selected Track Send 4 volume | Selected Track Send 5 volume | Selected Track Send 6 volume | Selected Track Send 7 volume | Selected Track Send 8 volume | Selected track volume | -
Encoder push | Show/Hide FX slot 1 | Show/Hide FX slot 2 | Show/Hide FX slot 3 | Show/Hide FX slot 4 | Show/Hide FX slot 5 | Show/Hide FX slot 6 | Show/Hide FX slot 7 | Show/Hide FX slot 8 | - | -
Button upper | Selected Track Record Arm | Selected Track Mute | Selected Track Solo | Clear All Solo | Cycle  Selected Track Auto Mode | Selected Track Toggle VCA Spill | Selected Track Toggle Pin | - |  | Layer A/Control [X] GoZone Home
Button lower | Track Bank -1 | Track Bank +1 | Go to previous marker/project start | Go to next marker/project end | Cycle Timeline | Stop | Play | Record |  | Layer B/Shift [-]
Hold+Button lower | - | - | Go to start of project | Go to end of project | - | Toggle VCA Mode | - | - | - | -

## Control+Shift+"Home" layout
 -| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Layer
 -| - | - | - | - | - | - | - | - | ----- | -----
Encoder | Selected Track Send 1 Pan | Selected Track Send 2 Pan | Selected Track Send 3 Pan | Selected Track Send 4 Pan | Selected Track Send 5 Pan | Selected Track Send 6 Pan | Selected Track Send 7 Pan | Selected Track Send 8 Pan | Selected track volume | -
Encoder push | - | - | - | - | - | - | - | - | - | -
Button upper | Selected Track Send 1 Mute | Selected Track Send 2 Mute | Selected Track Send 3 Mute | Selected Track Send 4 Mute | Selected Track Send 5 Mute | Selected Track Send 6 Mute | Selected Track Send 7 Mute | Selected Track Send 8 Mute | - | Layer A/Control [X]GoZone Home
Button lower | Track Bank -1 | Track Bank +1 | Go to previous marker/project start | Go to next marker/project end | Cycle Timeline | Stop | Play | Record | - | Layer B/Shift [X]
Hold+Button lower | - | - | Go to start of project | Go to end of project | - | Toggle VCA Mode | - | - | - | -

Enjoy!
