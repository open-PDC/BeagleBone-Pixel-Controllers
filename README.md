# Copyright and Disclaimer

Copyright: PDC

This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable conditions


# PDC Pixel Controllers

PDC Pixel Controllers must be used with either a BeagleBone Black (Rev C), BeagleBone Black Wireless or a BeagleBone Green (not the wireless version) and all run on FPP software. **Tested ready to run Controllers with FPP installed on a MicroSD card can be purchased from me direct** however, the design files are open source and available on GitHub. EasyEDA was used for the PCB designs.

## Controller Boards

All board variants have a total of 48 Ports for Pixel Strings. I2C connections are provided for a DS3231-AT24C32 RTC and a SSD1306 128x64 OLED Display.

**Note:** All board variants are powered by **5volts DC!** and only supply the Data signal, they **do not supply power for pixels!** To power pixels, an F8-Distro Board or similar, or an Auto/Marine Fuse box should be used.

* [**PDC-48-Flex**](PDC-48-Flex/README.md) - PDC-48-Flex A modular stacked system similar to the Holiday Coro Flex system but **NOT COMPATIBLE!** with up to 12 Differential Ports.

## Expansion Boards

* [**PDC-Expansion Boards**](Expansion-Boards/README.md) - PDC-48-Flex A modular stacked system similar to the Holiday Coro Flex system but **NOT COMPATIBLE!** with up to 12 Differential Ports.
