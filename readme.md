Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### License summarised:
This license enables reusers to distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, and only so long as attribution is given to the creator. If you remix, adapt, or build upon the material, you must license the modified material under identical terms. CC BY-NC-SA includes the following elements:

BY: credit must be given to the creator.
NC: Only noncommercial uses of the work are permitted.
SA: Adaptations must be shared under the same terms.

If you wish to commercially exploit this design, contact me on info@mikeholscher.nl.

# mikecinq

Welcome to my mikecinq GitHub repo!

- In the files folder you can find all the files to build your own mikecinq.
- This repo also contains all the files to build your own ZMK firmware using GitHub Actions.
- You can customize your layout using ZMK Keymap Editor or ZMK Studio.

What do you need to build your mikecinq:

- 1x mikecinq PCB
- 1x mikecinq case
- 1x nice!nano v2 or similar
- 36x Kailh PG1316S switch
- 36x 1N4148W SOD-123 diodes
- 1x MSK12C02 power switch
- 1x 301230 lipo battery
- 19x M1.6x2 screws

optionally, to improve ESD performance, 0603 (1608 metric) SMD components of any value:
- 1x resistor
- 1x capacitor
- 1x ferrite bead

required tools (continue reading for explanation)
- hotplate
- solder paste
- soldering iron
- solder
- flux
- stationary drill
- countersinking drill bit
- screwdriver to match your screws

### about the pcb
Somehow, JLCPCB online viewer renders the PCB preview weirdly. Maybe because of the many cutouts including castellated holes, I don't know. I checked the files with a JLC service employee, and they are fine. Remember to order a 0.8mm PCB and select castellated holes in the options.

### about soldering
I STRONGLY advise to use a hotplate for soldering the switches to the top of the PCB. You really have to be a pro to solder the switch frames to the PCB by hand. Reworking a switch is impossible using an iron because of the large thermal mass of the metal switch frame. Surface mounting using a hotplate and the thin PCB is the easiest and neatest way of soldering I have ever done. The one that should be soldered by hand are the switch contacts though the holes on the bottom of the PCB. This is done on purpose because surface mounting these switch contacts reliably somehow is very hard. You can choose to do the nice!nano by hand or surface mount it too. I used Chipquik TS391LT No-clean soldering paste lead-free and Chipquik CQ4LF fluxpen.

### about the screws
For thinnest (5mm complete height) use countersunk screws with extra small heads. If you will be using bumpers on the bottom you can also opt for thin head, non-countersunk screws. I you want to go countersunk, you need a countersinking drill bit to make countersunk holes in the PCB. I strongly advise to do this on a stationary drill as countersinking with a hand drill makes terrible asymmetric holes. I used a 6.3mm size countersinking drill bit, placed the PCB on a steel sheet, and just drilled down in the PCB until the drill bit hit the steel sheet, to make all countersunk holes the same depth/size.





