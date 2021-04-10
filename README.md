# RPI-Weatherstation

This application serves as a personal weatherstation that utilizes the Raspberry Pi SBC.  It provides an interface for a custom Home Assisant/Smart Home Manager system.  It will utilize a custom PCB to provide a simple interface between the RPi and the sensors.  

________________

### [Hardware]():

The following is a list of possible hardware. This list will be updated as more options are discovered and will be eventually be replaced with the list of decided hardware once determined.
- Sensors:
	- Temp, Humidity, Pressure:
    - BME280
    - DS18B20
  - Anemometer:
  - Wind Vein:
  - Rain Gauge:
  - Light:
  - UV:
  - Rain:
  - Rainfall Accumulation?:
- ICs:
  - ADC:
  	- MCP3008
- Connectors:
  - RJ11
  - Screw Terminals
  - 16 pin DIP connector
- PCBs:

### [Software]():

Interfaces for remote access:
- RESTful API
- A custom TCP connection protocol
- SSH with public key verification

The following is a list of software/application requirements, this list may change depending on which language is ultimately used to write the Weatherstation software:
- Database:
  - MariaDB
  - PostgreSQL
  	- Npgsql (if using .Net)
- Runtimes/Languages:
  - Net5.0 (if using .Net Core)
  - C/C++
  - Python


