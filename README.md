# modification_CAMXTOOL-V3.5-or-V3.4--cnc-board-for-FW-update
How to FW upgrade:
1.) Insert 1kOhm SMD resistor into D12 wire (see attached picture)
2.) download GRBL-CNC-board .HEX file (https://github.com/gnea/grbl/releases :: grbl_v1.1h.20190825.hex) [this is the last at now..]
   'Extreme Burner' howto: https://www.instructables.com/Hacking-EXtreme-Burner-for-AVR-Atmega-Devices-Prog/
   'Extreme Burner' info: https://extremeelectronics.co.in/software/extreme-burner-avr-1-3-beta-test/
3.) download 'Extreme Burner 1.4.3': http://digital-wizard.net/files/extreme_burner_avr_v1.4.3_setup.exe (working successfully :)
4.) using USBasp board (I bought it from Aliexpress...)
5.) save original Flash,EEPROM files using 'Extreme Burner'/read all & save functions
6.) do FW upgrade on CAMXTOOL-V3.5-or-V3.4--cnc-board using 'Extreme Burner' & USBasp programmer
