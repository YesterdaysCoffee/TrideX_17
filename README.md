# TrideX_17
Two headed verson of Trident, aka IDEX Trident.  This is not intended for novice users, kits and tutorials are not available.  Documentation will be minimal.  My main goal is to print one filament with a support filament.  Klipper now supports dual head printing for printing two copies at a time.  At some time in the future I will add a method to indepentantly adjust the height of the second Head.

![Front View.](images/front%20left.png)

This is an updated version of TrideX by [eddietheengineer](https://github.com/FrankenVoron/Tridex).

Active developement of IDEX macros can be found here: [joseph-greiner's IDEX code][https://github.com/joseph-greiner/tridex_mods/tree/main/printer_configuration]  (as of 2024-7-16).

# Version 0.7
This version uses my favored toolhead, probe, hotend and endstop switches.  Depending on popularity and demand, other options can be included.
Assembly depends on using 3mm and 5mm heat set inserts, some stls have variations using 5mm nuts.
Toolhead: Dragon Burner (it is relatively narrow)
Bed probe: PCB Klicky
Hotend: Rapido HF, other non-high-flow HE's will likely work
Endstops: Mecanical snap switches, Imron D2HW-A201D.
Toolhead wiring?  CANbus only (well, maybe USB...)

# Features and Improvements:
```
NEMA 17 steppers for X and Y
Belted Z using standard NEMA 17 motors and standard design from VORON Design and MathmaticalPotato, with changes.
Improved belt path and belt assembly
```
# Skirts & Corners: 
```
Optional power switch on sides
USB port in front skirts
LED power switch and dimmer on front skirts, independent from main power switch
```
Electronics bay accessible from the chamber (no more flipping upside down)

# Sizing considerations:
A good starting poing is a 250mm X 250mm build plate with frame size of 350mm width X 250mm depth.
The extra 100mm width and narrow tool heads like the Dragon Burner gives the idle tool head space to park out-of-the-way. An additional 50mm depth is not a bad idea.
Frame Size uses standards from Voron Trident: 250, 300 & 350mm with the addition of 400mm for X axis and 200mm on Y axis.  Note, the rear gantry support extrusion is shorter than standard.
Warning: 200mm depth will make fitting electronics a challange (it didn't work for me).

# The BOM is here:
(TridX-17 BOM)(https://docs.google.com/spreadsheets/d/1CbDP7zm5K3GdYLsManCU1-5Ye_r_lTrwqWS-yqpU0u4/edit?usp=sharing)

# Notes:
-->Many STL's found here are not compatible with anything else.  The Z-drive, XY-drive assembly and XY joints have all been tweeked for alignment, clearance and assembly.
-->Using a square build plate will be easiest to source.
-->My Firmware files (printer.cfg) are still in developemnt, use them as a starting point for your build.
-->I planned a build volumn of 250 x 250 x 200 (length x width by height).
-->Use the CAD file for assembly guidance only, the STL's in the CAD may be out of date.

# To do:
```
Add folding deck to CAD
Include detailed description of certain parts, such heat insert size in the BOM
Add photos, well duh.
Ponder improvement in ease of belt threading for XY drives.
Add assembly tips and tricks
```

# Got Comments, suggestions, gripes, pizza, praise, flames, offers to help?
Mac McCaskie --> <NameNoSpaces> yahoo com (you know where to put the punctuation)

Mostly I need someone else to assemble this and critique the process.
