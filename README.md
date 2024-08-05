# TrideX_17
Two headed version of Trident, aka IDEX Trident.  This is intended for experienced users.  Klipper now supports copy printing for printing two copies at a time, however leveling nozzles can be tricky.  In the future a method to adjust the height of the second head will be added.

![Front View.](images/front%20left.png)

This is an updated version of TrideX by [eddietheengineer](https://github.com/FrankenVoron/Tridex).

Active development of IDEX macros can be found here: [joseph-greiner's IDEX code](https://github.com/joseph-greiner/tridex_mods/tree/main/printer_configuration)  (as of 2024-7-16).

# Version 0.7
This version uses my favored tool-head, probe, hot-end and end-stop switches.  Depending on popularity and demand, other options can be included.
Assembly depends on using 3mm and 5mm heat set inserts, some stls have variations using 5mm nuts.
  - Tool-head: Dragon Burner (it is relatively narrow)
  - Bed probe: PCB Klicky
  - Hot-end: Rapido HF, other non-high-flow HE's will likely work
  - End-stops: Mechanical snap switches, Imron D2HW-A201D.
  - Tool-head wiring?  CANbus only (well, maybe USB...)

# Features and Improvements:
  - NEMA 17 steppers for X and Y
  - Belted Z using standard NEMA 17 motors and standard design from VORON Design and MathmaticalPotato, with changes.
  - Improved belt path and belt assembly

# Skirts & Corners:
  - Optional power switch on sides
  - USB port in front skirts
  - LED power switch and dimmer on front skirts, independent from main power switch

  - Electronics bay accessible from the chamber (no more flipping upside down)

# Sizing considerations:
A good starting point is a 250mm X 250mm build plate with frame size of 350mm width X 250mm depth.
The extra 100mm width and narrow tool heads like the Dragon Burner gives the idle tool head space to park out-of-the-way. An additional 50mm depth is not a bad idea.

Frame Size uses standards from Voron Trident: 250, 300 & 350mm with the addition of 400mm for X axis and 200mm on Y axis.  Note, the rear gantry support extrusion is shorter than standard.
Warning: 200mm depth will make fitting electronics a challenge (it didn't work for me).

# The BOM is here:
[TridX-17 BOM](https://docs.google.com/spreadsheets/d/e/2PACX-1vSPtPn4Brcn_vidSKCY5Uy1v6KD8oOBtxnAigVPllrFKF_peJibIDPYqSZS3NHdLf7wJWIKfuaN0-26/pubhtml)

# Notes:
  - Many STL's found here are not compatible with anything else.  The Z-drive, XY-drive assembly and XY joints have all been tweaked for alignment, clearance and assembly.
  - Using a square build plate will be easiest to source.
  - My Firmware files (printer.cfg) are still in development, use them as a starting point for your build.
  - I planned a build volume of 250 x 250 x 200 (length x width by height).
  - Use the CAD file for assembly guidance only, the STL's in the CAD may be out of date.

# To do:
- [] Add folding deck to CAD
- [] Include detailed description of certain parts, such heat insert size in the BOM
- [] Add more photos, well duh.
- [] Ponder improvement in ease of belt threading for XY drives.
- [] Add assembly tips and tricks
- [] Find micro-adjustable tool-head leveling system

# Got Comments, suggestions, gripes, pizza, praise, flames, offers to help?
Mac McCaskie --> yahoo com (no spaces, you know where to put the punctuation)

Please drop a line if you build this, thanks.
