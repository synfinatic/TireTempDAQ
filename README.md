# TireTempDAQ

## About
This project is designed to add IR  temperature sensors to your existing data logger.  The initial design for this project will support up to 4 sensors and output 4 linear analog outputs (0 to 4.096V) to your data logger (GPX Pro, AiM, Race-Technology, AEM, MoTeC, GEMS, etc).

This project will include three main parts:

 * CadSoft Eagle files for the PCB designs
 * Arduino compatible software for the [PRJC Teensy-LC](http://www.prjc.com/teensy/teensyLC.html) micro-controller
 * [Autodesk Fusion 360](http://www.autodesk.com/products/fusion-360/overview) CAD designs of the cases for the sensor & controller modules which can then be manufactured via 3D printing ABS/PLA or CNC aluminum.
 
## Design
The key component will be the [Melexis MXL90614](http://www.melexis.com/Infrared-Thermometer-Sensors/Infrared-Thermometer-Sensors/Digital-plug--play-infrared-thermometer-in-a-TO-can-615.aspx) IR temperature sensor.  This sensor is a small yet accurate IR sensor able to measure the temperature of other objects without touching them- perfect for tires on a car or motorcycle!

Each sensor sends it's data via a thin single cable of 4 wires to the "brains" which decodes the digital signals from each sensor and then relays that to your data logger via a standard linear analog output.  This conversion process ensures that TireTempDAQ will be compatible with virtually any data aquision system you can imagine!

## License
All files are released under the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.en.html).