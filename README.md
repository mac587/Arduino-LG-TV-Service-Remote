# Arduino-LG-TV-Service-Remote
Simple arduino sketch to transmit IR LG TV service menu command 2018-2020 model years

Works with mega328 based arduinos, Uno, Nano, Pro mini etc 

Prerequisites:
1. Build hardware (see wiki)
2. Arduino IDE
3. IRremote library: Sketch, include library, manage labraries, search for "irremote" install
4. in_start_sketch.txt from main repository

Note: Arduino will continuously send the command every 5 seconds while connected to power.

To go back or exit service menus, send command again
