# Behringer X-Touch Mini Reaper CSI Template

## Things You need

- [Cockos Reaper](https://www.reaper.fm/)
- [Control Surface Integrator - CSI Reaper Plugin](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki)
- [Behringer X-Touch Mini](https://www.behringer.com/product.html?modelCode=P0B3M) control surface

## Installation

1. Install Reaper
2. Install CSI, [see documentation](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Installation)
3. Put CSI folder and it's files into the Reaper Resource Path\CSI folder keeping the structure. If you're already running CSI and currently have a working configuration, do NOT overwrite your current CSI.ini with the one provided. The Midi surface configuration should be

- 8 Number of Channels,
- 0 Channel Start position,
- 8 Number of Sends,
- 8 Number os FX Menu,
- Surface: XTouchMini_MC_MODE.mst,
- Zone Folder: XTouchMini_MC_MODE.

4. Do not forget to disable X-TOUCH MINI In/Out MIDI ports in Reaper > Option > Preferences > MIDI devices
5. X-Touch Mini needs to be in MC mode (MC MODE LED is lit). You can change from normal mode with powering up and holding down MC button, until the LEDs flash.

## Layouts

1. **"Home"** zone, where banks of 8 channels controls are accessible.
2. **"Selected Track"** zone, where the selected track's parameters are accessible.
3. **"FX zones"** where the focused effect parameters are accessible.

- The layouts altered by the _Shift (LayerB)_ and _Control (LayerA)_ modifiers.
- Change between **"Home"** and **"Selected Track"** layout by Control+ButtonLower1 button.
- **"FX zones"** are activated automatically by focusing on the effect window.

### "Home" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Track 1 Volume | Track 2 Volume | Track 3 Volume | Track 4 Volume | Track 5 Volume | Track 6 Volume | Track 7 Volume | Track 8 Volume | Master Track Volume | - |
| **Encoder push** | - | - | - | - | - | - | - | - | - | - |
| **Button upper** | Track 1 Solo | Track 2 Solo | Track 3 Solo | Track 4 Solo | Track 5 Solo | Track 6 Solo | Track 7 Solo | Track 8 Solo | - | Control [-] |
| **Button lower** | [Track Bank -8](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TrackBank) | [Track Bank +8](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TrackBank) | Go to previous marker/project start | Go to next marker/project end | [Cycle Timeline](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/CycleTimeline) | [Stop](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Play](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Record](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | - | Shift [-] |
| **[Hold](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Modifiers#hold)+Button lower** | - | - | Go to start of project | Go to end of project | - | - | - | - | - | - |

### Shift+"Home" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **[Encoder](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/MCUTrackPan)** | Track 1 Pan/Pan Width | Track 2 Pan/Pan Width | Track 3 Pan/Pan Width | Track 4 Pan/Pan Width | Track 5 Pan/Pan Width | Track 6 Pan/Pan Width | Track 7 Pan/Pan Width | Track 8 Pan/Pan Width | Master Track Volume | - |
| **[Encoder push](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/MCUTrackPan)** | Encoder 1 Pan/Pan width | Encoder 2 Pan/Pan width | Encoder 3 Pan/Pan width | Encoder 4 Pan/Pan width | Encoder 5 Pan/Pan width | Encoder 6 Pan/Pan width | Encoder 7 Pan/Pan width | Encoder 8 Pan/Pan width | - | - |
| **Button upper** | Track 1 Mute | Track 2 Mute | Track 3 Mute | Track 4 Mute | Track 5 Mute | Track 6 Mute | Track 7 Mute | Track 8 Mute | - | Control [-] |
| **Button lower** | Track Bank -1 | Track Bank +1 | Move cursor left to grid division | Move cursor right to grid division | Toggle metronome | [Toggle VCA Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill#togglevcamode) | Solo in front | Insert marker | - | **Shift [X]** |
| **Hold+Button lower** | - | - | - | - | Show metronome settings | - | - | - | - | - |

### Control+"Home" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Track 1 Volume | Track 2 Volume | Track 3 Volume | Track 4 Volume | Track 5 Volume | Track 6 Volume | Track 7 Volume | Track 8 Volume | [FocusedFXParam](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/FocusedFXParam) | - |
| **Encoder push** | Show/Hide FX slot 1 | Show/Hide FX slot 2 | Show/Hide FX slot 3 | Show/Hide FX slot 4 | Show/Hide FX slot 5 | Show/Hide FX slot 6 | Show/Hide FX slot 7 | Show/Hide FX slot 8 | - | - |
| **Button upper** | Track 1 Select | Track 2 Select | Track 3 Select | Track 4 Select | Track 5 Select | Track 6 Select | Track 7 Select | Track 8 Select |  | **Control [X]** |
| **Button lower** | GoZone "Selected track" | Close all FX windows | - | - | Toggle count-in | - | Clear All Solo | Delete marker |  | Shift [-] |
| **Hold+Button lower** | - | - | - | - | - | - | - | - | - | - |

## Control+Shift+"Home" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Track 1 Volume | Track 2 Volume | Track 3 Volume | Track 4 Volume | Track 5 Volume | Track 6 Volume | Track 7 Volume | Track 8 Volume | Master Track Volume | - |
| **Encoder push** | - | - | - | - | - | - | - | - | - | - |
| **Button upper** | Track 1 Record | Track 2 Record | Track 3 Record | Track 4 Record | Track 5 Record | Track 6 Record | Track 7 Record | Track 8 Record | - | **Control [X]** |
| **Button lower** | Refresh all surfaces | - | Go to previous marker/project start | Go to next marker/project end | [Cycle Timeline](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/CycleTimeline) | [Stop](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Play](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Record](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | - | **Shift [X]** |
| **Hold+Button lower** | - | - | - | - | - | - | - | - | - | - |

### "Selected Track" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Send 1 volume | Send 2 volume | Send 3 volume | Send 4 volume | Send 5 volume | Send 6 volume | Send 7 volume | Send 8 volumme | Selected Track Volume | - |
| **Encoder push** | Open FX slot 1 | Open FX slot 2 | Open FX slot 3 | Open FX slot 4 | Open FX slot 5 | Open FX slot 6 | Open FX slot 7 | Open FX slot 8 | - | - |
| **Button upper** | Record Arm | Mute | Solo | Clear All Solo | Invert polarity | [VCA Spill](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill) | [Cycle Track Auto Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Automation-Actions) | [Toggle Pin](<https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TogglePin-(Pinning-Tacks)>) | - | Control [-] |
| **Button lower** | [Track Bank -1](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TrackBank) | [Track Bank +1](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TrackBank) | Go to previous marker/project start | Go to next marker/project end | [Cycle Timeline](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/CycleTimeline) | [Stop](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Play](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Record](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | - | Shift [-] |
| **[Hold](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Modifiers#hold)+Button lower** | - | - | Go to start of project | Go to end of project | - | - | - | - | - | - |

### Shift+"Selected Track" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Send 1 Pab | Send 2 Pan | Send 3 Pan | Send 4 Pan | Send 5 Pan | Send 6 Pan | Send 7 Pan | Send 8 Pan | Selected Track VolumPane | - |
| **Encoder push** | Open FX slot 1 | Open FX slot 2 | Open FX slot 3 | Open FX slot 4 | Open FX slot 5 | Open FX slot 6 | Open FX slot 7 | Open FX slot 8 | - | - |
| **Button upper** | Record Arm | Mute | Solo | Clear All Solo | Invert polarity | [VCA Spill](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill) | [Cycle Track Auto Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Automation-Actions) | [Toggle Pin](<https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TogglePin-(Pinning-Tacks)>) | - | Control [-] |
| **Button lower** | Track Bank -1 | Track Bank +1 | Move cursor left to grid division | Move cursor right to grid division | Toggle metronome | [Toggle VCA Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill#togglevcamode) | Solo in front | Insert marker | - | **Shift [X]** |
| **Hold+Button lower** | - | - | - | - | Show metronome settings | - | - | - | - | - |

### Control+"Selected Track" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Send 1 volume | Send 2 volume | Send 3 volume | Send 4 volume | Send 5 volume | Send 6 volume | Send 7 volume | Send 8 volumme | Selected Track Volume | - |
| **Encoder push** | Open FX slot 1 | Open FX slot 2 | Open FX slot 3 | Open FX slot 4 | Open FX slot 5 | Open FX slot 6 | Open FX slot 7 | Open FX slot 8 | - | - |
| **Button upper** | Record Arm | Mute | Solo | Clear All Solo | Invert polarity | [VCA Spill](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill) | [Cycle Track Auto Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Automation-Actions) | [Toggle Pin](<https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TogglePin-(Pinning-Tacks)>) | - | **Control [X]** |
| **Button lower** | GoZone "Home" | Close all FX windows | - | - | Toggle count-in | - | Clear All Solo | Delete marker |  | Shift [-] |
| **Hold+Button lower** | - | - | - | - | - | - | - | - | - | - |

### Shift+Control+"Selected Track" zone layout

| - | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | Fader | Modifier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Encoder** | Send 1 volume | Send 2 volume | Send 3 volume | Send 4 volume | Send 5 volume | Send 6 volume | Send 7 volume | Send 8 volumme | Selected Track Volume | - |
| **Encoder push** | Open FX slot 1 | Open FX slot 2 | Open FX slot 3 | Open FX slot 4 | Open FX slot 5 | Open FX slot 6 | Open FX slot 7 | Open FX slot 8 | - | - |
| **Button upper** | Record Arm | Mute | Solo | Clear All Solo | Invert polarity | [VCA Spill](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/VCA's-and-VCA-Spill) | [Cycle Track Auto Mode](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Automation-Actions) | [Toggle Pin](<https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/TogglePin-(Pinning-Tacks)>) | - | **Control [X]** |
| **Button lower** | Refresh all surfaces | - | Go to previous marker/project start | Go to next marker/project end | [Cycle Timeline](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/CycleTimeline) | [Stop](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Play](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | [Record](https://github.com/GeoffAWaddington/reaper_csurf_integrator/wiki/Transport-Actions) | - | **Shift [X]** |
| **Hold+Button lower** | - | - | - | - | - | - | - | - | - | - |

Enjoy!
