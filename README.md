DE0 ORPSoC
==========

This project is an addon I/O board for the Altera DE0-Nano.  It is meant to
be used as a development platform for the OpenRISC soft CPU.

The peripherals on the board are:

* Dual USB to UART
* RMII Ethernet
* SPI Ethernet
* RTC w/ battery backup (I2C)
* Thermal sensor (I2C)
* Micro SD card
* USB 1.1 Transceiver
* Reset button
* Status LEDs

All devices are powered at 3.3V from the DE0 regulators, though a set of
jumpers allow to power the DE0 itself from one of the USB ports of the I/O
board.

License
-------

This work is licensed under a Creative Commons Attribution-ShareAlike 3.0
License.

Contents
--------

    README      this file
    hardware/   source directory for the hardware design

Hardware
--------

All hardware files (schematic, layout and libraries) are in CadSoft Eagle
format.
