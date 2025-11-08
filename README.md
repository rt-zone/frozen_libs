# frozen_libs
libraries for modules and fonts for Display

Commands to build a firmware:
cd ~/micropython/ports/rp2
rm -f -rf build-RPI_PICO_W/
make clean
make BOARD=RPI_PICO_W USER_C_MODULES=modules/st7789_mpy/st7789
