# GH4PIN01 Module: MLAB to PixHawk 4PIN interface

![GH4PIN01 mounted on ALBASE](doc/src/img/GH4PIN01-small.jpg)


## Overview
The GH4PIN01 Module is a 4-pin adapter that converts JST-GH connectors, commonly used in [PixHawk](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf) avionics, to standard pin headers. This module includes two JST-GH connectors and supports I2C or CAN bus communication, making it a versatile and essential component in the MLAB system for integrating various electronic devices.

![GH4PIN01 top view](doc/gen/img/GH4PIN01-top.png) ![GH4PIN01 bottow view](doc/gen/img/GH4PIN01-bottom.png)


## Features
- **Dual JST-GH Connectors**: Provides increased connectivity options.
- **I2C and CAN Bus Support**: Ideal for communication in Pixhawk avionics and other devices.
- **MLAB I2C Standard**: Pin header follows the GND-SDA-+5V-SCL-GND configuration, preventing device damage from reversed cables.
- **User-Friendly Design**: Simplifies connections without complex modifications.
- **High Compatibility**: Integrates seamlessly with MLAB modular components.
- **Durable Construction**: High-quality materials for reliable and robust performance.

## Specifications
- **Connector JST-GH**: 4-pin JST-GH [PixHawk standard](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf)
- **Connector HEADER**: Standard 2.54mm pin header (4-pin)
- **Pinout**: GND SDA +5V SCL GND
- **Operating Temperature Range**: -40°C to 85°C

## Possible uses
- Integrating custom avionics into Pixhawk drone projects.
- Connecting JST-GH devices to MLAB standard pin header-based systems.
- Prototyping and development with MLAB modular components.
- I2C or CAN bus communication setups.
