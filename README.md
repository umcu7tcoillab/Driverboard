# Driverboard for 7T MRI (Philips Achieva)

## About us
This design has been made by the coil-lab of the High Field MRI Group of the UMC Utrecht in the Netherlands, where we make hardware to support our researchers. We are part of a research group which means we feel the need to open up some of our designs to whomever can make use of it, to further the research of MRI applications.


## The design
This project contains a driverboard made for our 7T Philips Achieva MRI system. It has been tested inside the magnetic field of the 7T MRI. 

The driverboard is used as an interface between the MRI scanner and the RF coil. It provides the following functions:
- Provides the ID code of the coil.
- Switches relatively high current DC signals for PIN-diode switching. 
- Reports coil malfunctions to the scanner system. Special care has been taken to ensure this malfunction check is as robust as possible. 
- Stable reference voltages, which are used to help facilitate remote PIN-diode malfunction checks using window comparators on external boards.
- Two outputs: Detune and TR-switch voltages
- 4A maximum current on the -5V per output.

The design and subsequent drawing has been done in Kicad 5.1.5.


## Download
Gerber and BOM production files for the latest _field tested_ version of the PCB can be found in the 'Releases' page, or by following [this link](https://github.com/umcu7tcoillab/Driverboard/releases/latest). 
You can also make your own production files by downloading the Kicad project and generating them, but these are not guaranteed to have been field tested.


## Images
**3D Image**
<img src="Images/3D.png?raw=true"/>
