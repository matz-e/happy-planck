# Happy Plank

Firmware for the Happy Planck keyboard with less keys than a regular
Planck.

## Installation

    git submodule init
    git submodule update
    git clone git@github.com:ChibiOS/ChibiOS.git tmk_keyboard/tmk_core/tool/chibios/ChibiOS
    git clone git@github.com:ChibiOS/ChibiOS-Contrib.git tmk_keyboard/tmk_core/tool/chibios/ChibiOS-Contrib

## Building and Flashing

    make -f Makefile.3.2
    sudo ~/.local/bin/teensy_loader_cli --mcu=mk20dx256 -w build/planck_32.hex
