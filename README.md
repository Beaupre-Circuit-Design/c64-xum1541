# C64-XUM1541

# Introduction

This project is a collections of 3 subprojects, XUM1541, an OpenCBM compatible interface, a VIA adapter to add a parallel interface to a 1541 (SpeedDos and XUM1541 Compatible) and a C64 User Port adapter for the paralle interface (SpeedDos compatible).

If the only thing you need is to backup and restore your floppies via a PC, only the XUM1541 is needed, with the optional VIA adapter if you want to make things a bit faster. The User Port adapter require a ROM upgrade for the C64 and the 1541 (which can be done with a ROM adapter like the [23xx Adapter](https://github.com/Beaupre-Circuit-Design/23xx-Adapter).

|Module           |PC |C64|SpeedDos|Description                                            |
|-----------------|---|---|--------|-------------------------------------------------------|
|[XUM1541](xum1541/)|Yes|N/A|N/A|Module for backing up and restoring floppies disk to PC|
|[VIA Adapter](xum1541-parallel-adapter/)|Optional|N/A|Required|Parallel interface for the 1541 disk drive|
|[User Port Adapter](xum1541-via-adapter)|N/A|N/A|Required|Parallel interface for the C64 user port|
|[23xx Adapter](https://github.com/Beaupre-Circuit-Design/23xx-Adapter)|N/A|N/A|Required|ROM adapter needed to install the SpeedDos Rom, needed to be done on both the C64 and the 1541|

See each project for build details.

# Licence

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

# Revision History

|Revision  |Description                    |
|:--------:|-------------------------------|
|1.0       |Initial prototype              |
|2.0       |Add bank switching header      |