# Overview 
This repository contains the files required to fabricate the AirMeter.io Sensor Assembly PCB (Printed Circuit Board). This board connects the various sensor components without complicated & time consuming soldering of wires.

It makes a 10 minute job of what was a very labourious manual execerise preiviously.

Using these files the PCBs can be ordered from third party manufacturers at an insignificant cost.

<div>
<img style="height: 150px" src="https://raw.githubusercontent.com/airmeter-io/SensorAssembly/main/Images/Sensor%20Assembly%20v1.0-Top.svg" />
<img style="height: 150px" src="https://raw.githubusercontent.com/airmeter-io/SensorAssembly/main/Images/Sensor%20Assembly%20v1.0-Bottom.svg" />
</div>


# Ordering

As the PCB is small they must be ordered as "panelised boards". This means printing multiple PCBs on a single panel which has lines cut in a grid pattern so that it can be broken appart into the individual boards.

The test order for this design was done using JLCPCB and 5 panels each containing 6 boards (2 rows of 3) giving a total of 30 Sensor Assemblies. For indicative purposes this order came in at approximately €35 including delivery & VAT to EU.

Any suitably equiped PCB supplier should be able to print & panelise the gerber files within this repository. Instructions for individual suppliers will be added as successful orders have been made.

It is advisable to consult someone experienced with designing & ordering PCBs before making an order. 

## JLCPCB Instructions

First start a new PCB quote and upload the Gerber file (The zip file from the GerberFiles folder). The dimensions 30mm x 70mm will be auto detected and a picture of the two sides of the PCB will be displayed. Now make the following changes:-
<a href="https://github.com/airmeter-io/SensorAssembly/raw/main/Images/JLCPCB.png"><img src="https://github.com/airmeter-io/SensorAssembly/raw/main/Images/JLCPCB.png" style="width: 125px;" /></a>


- Change "Delivery Format" to "Panel by JLCPCB".
- Change "Column" under "Panel Format" to 3
- Change "Row" under "Panel Format" to 2
- Choose your preferred color.

The above numbers will provde 6 PCBs per assembly and 5 panels giving a total of 30 boards. You may adjust these within JLCPCBs own limits to suit your needs.



# Supported Sensors

These boards are layed out to work with the following sensors:-
- 3.3v I2C CO2 Sensors
    - Senseair Sunrise: 006-0-0007 (Recommended)
    - Senseair Sunrise: 006-0-0008 (Recommended)
    - Sensirion SCD30
- Temperature, Pressure, Humidity
    - BME 280 (Recommended)
    - BME 680 (Includes VOC)
    - BMP 280 (No pressure)
    


# Disclaimer

In using these design files for any purpose you assume all responsibility & risks. Any use MUST be done under the guidance & watch of those with the requisite skills. These designs may contain errors.

Please see the GNU GENERAL PUBLIC LICENSE Version 3 for license conditions.




