# Solheim68

![Solheim68 PCB](https://i.imgur.com/iCpyETy.png)
This PCB is a direct replacement designed for the VA68M (Mini-USB) from Varmilo. Use this PCB as you wish, the license allows commercial use.  
Unfortunately it was impossible to support PCB mounted stabilizers on this one.

## Features
- Compatible with QMK Firmware
- More layout support (only with custom plate)

## Supported layouts
![Supported layouts of the Solheim68](https://i.imgur.com/L9mpXFS.png)

## Building
If you feel like building a few of these PCBs yourself, go to the 'Releases' tab and download the latest gerber files. Order those at your favourite PCB manufacturer, get the components needed (see below) and solder them on! A hot air station is not required but a soldering iron is. Flux is recommended.

## Opening the project
To open the files you will need the latest KiCAD nightly version.

## Bill of materials (BOM)
Amount is per PCB, multiply as needed.

| LCSC part # | Description   | Value | Package  | Amount |
| ----------- | ------------- | ----- | -------- | ------:|
| C128353     | Capacitor     | 0.1uF | 0805     | 4      |
| C131056     | Capacitor     | 4.7uF | 0805     | 1      |
| C215803     | Capacitor     | 1uF   | 0805     | 1      |
| C109001     | Diode         |       | 0805     | 72     |
| C145778     | USB Connector |       | SMD/THT  | 1      |
| C103904     | Resistor      | 10K   | 0805     | 2      |
| C325772     | Resistor      | 22    | 0805     | 2      |
| C44854      | MCU           | 32U4  | QFP-44   | 1      |
| C341521     | Resonator     | 16MHz | SMD      | 1      |
| C92584      | Switch        |       | SMD      | 1      |
