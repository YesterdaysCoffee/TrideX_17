# TrideX_17
Two headed version of Trident, aka TrideX. Changes include: NEMA 17 steppers for X & Y axis & improved belt assembly.  Generally intended for experienced builders due to lack of step-by-step instructions.  Klipper now supports copy printing for printing two copies at a time, however leveling nozzles can be tricky.  In the future a method to adjust the height of the second head will be added.

![Front View.](images/front%20left.png)

This is an updated version of TrideX by [eddietheengineer](https://github.com/FrankenVoron/Tridex).

Active development of IDEX macros can be found here: [joseph-greiner's IDEX code](https://github.com/joseph-greiner/tridex_mods/tree/main/printer_configuration)  (as of 2024-7-16).

# Version 0.9
This version uses my favored tool-head, probe, hot-end and end-stop switches.  Depending on popularity and demand, other options can be included (contact me).
Assembly depends on using 3mm and 5mm heat set inserts, some stls have variations using 5mm nuts.  My build used the following and I encourage you to use your favored accessories:
  - Tool-head: Dragon Burner (it is relatively narrow)
  - Bed probe: PCB Klicky, Chartographer 3D being tested
  - Hot-end: Rapido HF, other non-high-flow HE's will likely work
  - End-stops: Mechanical snap switches, Imron D2HW-A201D.
  - Tool-head wiring?  CANbus only (well, maybe USB...)

# 9mm Belts?
Yes, I have started drawing up a gantry using 9mm X/Y belts.  The X linear rail might change.

# Features and Improvements:
  - NEMA 17 steppers for X and Y
  - Belted Z using standard NEMA 17 motors and standard design from VORON Design and MathmaticalPotato, with changes.
  - Improved belt path and belt assembly

# Skirts & Corners:
  - Optional power switch on sides
  - USB port in front skirts
  - LED power switch and dimmer on front skirts, independent from main power switch (warning, I will probably remove this since I was not happy with the results)

  - Electronics bay accessible from the chamber (no more flipping upside down)

# Sizing:
My recommended sizing.  Take your build plate size and:
  - Add 100mm to X (width)
  - Add 50mm to Y (depth)

Typical sizes using square build plates:
  - 200mm, use 250mm sides & 300mm Front/rear, note: electronics bay will be very croweded.
  - 250mm, use 300mm sides & 350mm Front/rear
  - 300mm, use 350mm sides & 400mm Front/rear
  - 350mm, stls have not been included, a 9mm belt version is in the works, and will scale up better.
  - 
A good starting point is a 250mm X 250mm build plate with frame size of 350mm width X 300mm depth.

# Random notes:
- Trident's original Z-drive fits fine, use the original Trident skirts and electronic bay assembly.
- Conversion of a Trident to TrideX-17 has been done. I don't know if the same build plate was used but I'd suggest using a smaller build plate.
- Extra width gives enough space for the idle toolhead to park out if the way.
- Extra depth is needed for the wider X/Y drive assembly and any additional accessories you will use back there. 

In truth any size can be built, it's the skirts which limit frame size options.  Be aware with a very long X-gantry might be problematic.

Frame Size uses standards from Voron Trident: 250, 300 & 350mm with the addition of 400mm for X axis and 200mm on Y axis.  Note, the rear gantry support extrusion is shorter than standard.
Warning: 200mm depth will make fitting electronics a challenge (it didn't work for me).
# Extra Files:
[TridX-17 BOM](https://docs.google.com/spreadsheets/d/e/2PACX-1vSPtPn4Brcn_vidSKCY5Uy1v6KD8oOBtxnAigVPllrFKF_peJibIDPYqSZS3NHdLf7wJWIKfuaN0-26/pubhtml) updated 11-11-2024.

[TridX-17 Change Log](https://docs.google.com/spreadsheets/d/e/2PACX-1vTWaBhZNpjk6NEAdd5VofSHPy5cyr7JOfr-hXRtq54E_nhzI_LgpVOrBIPudIq8-uXfLt_XMnXbr9e0/pubhtml) updated 11-11-2024.

# Notes:
  - Many STL's found here are not compatible with anything else.  The Z-drive, XY-drive assembly and XY joints have all been tweaked for alignment, clearance and assembly.
  - Using a square build plate will be easiest to source.
  - My Firmware files (printer.cfg) are still in development, please depend on [joseph-greiner's IDEX code](https://github.com/joseph-greiner/tridex_mods/tree/main/printer_configuration)
  - Use the CAD file for assembly guidance only, the STL's in the CAD may be out of date.

# To do:
- [] Add folding deck to CAD (piano hinges)
- [] Include detailed description of certain parts, such heat insert size in the BOM
- [] Add assembly tips and tricks
- [] Find micro-adjustable tool-head leveling system

# Got Comments, suggestions, gripes, pizza, praise, flames?  Trolls will be ignored.
Mac McCaskie --> yahoo com (no spaces, you know where to put the punctuation)

Please drop a line if you build this, thanks.
