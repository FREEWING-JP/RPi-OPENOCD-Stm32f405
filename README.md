# RPi-OPENOCD-Stm32f405
Raspberry Pi based bit-banging utilizing BCM2835 configuration to upload pre-compiled binaries to Stm32f405 microcontrollers.  
Also works for most other chips thanks to OpenOCD's huge library of configs.

This Example, once totally finished will show the necessary steps to get OpenOCD JTAG/SWD debugger working on
a Raspberry Pi, and then follow through with the setup and flash of an Stm32f405 chip (ARM Cortex-M4 @ 168mhz)
like that used in the VESC opensource BLDC controller created by Benjamin Vedder.  Instead of having to use an
Stlinkv2 programmer, this configuration intends to replace it with a Raspberry Pi which most people have already
laying around.

This configuration is a work in progress, please use at your own risk as it is still in active development.

Prerequisites:
- Raspberry Pi B+, 2B, or 3B
- Running either Raspbian or Ubuntu Mate (add installation methods)
- Install dependencies (add list of dependencies and commands to install them)
- Installed ARM cross-compiler toolchain (add link to correct one)
- Compile OpenOCD from source (add instructions)
- Export udev rules (add instructions)
- Setup Instructions (add instructions)
- Wiring (add fritzing diagram)

This configuration is a work in progress, please use at your own risk as it is still in active development.
