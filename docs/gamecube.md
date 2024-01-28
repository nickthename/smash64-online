---
title: Gamecube Controller Setup
section: legacy
hide:
  - next
  - prev
  - search
  - tabs
---

# GameCube Controller Setup

These instructions are for configuring a GameCube controller using a Nintendo or Mayflash USB adapter. If you have a Raphnet gc to usb adapter, you can skip to [Configure Controller Plugin](#3-configure-controller-plugin).

[:fontawesome-brands-youtube: Optional Video Walkthrough](https://www.youtube.com/watch?v=4ntXPY4SqNQ){ .md-button data-md-color-primary="red" data-md-color-accent="red" }

### 1. Install Drivers
- Download and install [Wii U Adapter Driver](http://m4sv.com/page/wii-u-gcn-usb-driver)
- Select **WUP-028** form the drop down in Zadig
- **DO NOT INSTALL vJoy from here, it's old**
- Instead download and install the [latest vJoy](https://sourceforge.net/projects/vjoystick/)

### 2. Run Drivers
- Close Project64
- Run GameCube USB Adapter Driver and click `Start`
- This must *always* be running when you use Project64, it will be in your taskbar

### 3. Configure Controller Plugin
- Open Project64, go to Settings
- Select `N-Rage's Direct-Input8 V2 1.83` as your Controller Plugin
- Go to Options -> Configure Controller Plugin > Devices > Select `vJoy Device 1`
- Now you can setup your inputs.
- You may need to restart your computer if this doesn't work

#### Recommended Settings
- Real N64 Range: **unchecked**
- Range: **100%**
- Deadzone **10%**
<p></p>
- N-Rage's Z: Preferred Shield Trigger
- N-Rage's L: Remaining Trigger
- N-Rage's R: Z
- N-Rage's C Left: Y
- N-Rage's C Right: X

#### Tips for Analog Triggers
For triggers, you'll need to bind the digital press using the steps below. This may take a few tries to get right.

1. You need to press the trigger most of the way down (before it clicks)
2. Click the button your want to map in N-Rage
3. Fully press down trigger

!!! info "Guide Credits"
    This guide was originally written by Crovy.
