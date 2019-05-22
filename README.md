# grbl-plotter
GRBL Plotter, Adruino with GRBL Shield V3 

## Material:
- Arduino Uno R3
- GRBL Shield V3
- 2 Stepper Motor 1.8 degree
- 2 Stepper Driver A4988
- Tower Pro SG90 9g Micro servo 
- Print Parts download from https://www.thingiverse.com/thing:3636085

## Setup
- Download Arduino IDE from https://www.arduino.cc/
- Install and Open Arduino IDE
- Import MIGRBL.zip to libraries: Sketch > Include Library > Add .ZIP Library...
- Selected MIGRBL.zip to import
- Connect Arduino Uno R3 via USB cable, select File > Examples > MIGRBL > grblUpload
- Select correct information for board from Tools:
Board: "Arduino/Genuino Uno"
Port: USB port for Arduino Uno
Programmer: "AVRISP mkll"
- Click to button Upload

## Gcode Editor Tools Setup
- Download and setup Inkscape version 0.48.5 (https://inkscape.org/release/inkscape-0.48.5/)
- Unzip tools/MI Inkscape Extension.zip and copy all of file to inkscape extensions folder
MAC: ~/.config/inkscape/extensions/
WINDOW: ...

## Gcode Sender Tool
- GRBL Controller: https://github.com/zapmaker/GrblHoming/releases