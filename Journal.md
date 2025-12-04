KB75 Mechanical Keyboard Build Guide
Overview

The KB75 is an open-source 75 percent mechanical keyboard.
It supports hot swap switches, VIA and QMK firmware, optional RGB lighting and an optional rotary knob.
You can customize how it looks, feels and behaves.

Materials You Need

You will need the KB75 PCB, a microcontroller (RP2040 or Pro Micro with USB-C), MX compatible switches, stabilizers, diodes if the PCB requires them, a rotary encoder if you plan to use one and keycaps that fit a 75 percent layout.

Tools You Need

You will need a soldering iron, solder, flush cutters, tweezers, a USB-C cable and a computer.

Step 1: Preparing the PCB

Place the PCB on a clear and stable table.
If it requires loose diodes, solder those first.
Next, install any hot swap sockets if your version uses them.
Position the microcontroller carefully.
Solder a single pin first to hold it in place.
Once it is aligned correctly, solder the remaining pins.

(You can add a picture here of the PCB with components installed.)

Step 2: Installing Stabilizers and Switches

Install the stabilizers for the larger keys like spacebar, enter and backspace.
Press your switches into the PCB until they click and sit firmly.
Place the PCB inside the case to make sure everything aligns properly.
If it fits correctly, solder all the switches.

(You can add a picture here showing the switches installed.)

Step 3: Flashing the Firmware

There are two ways to flash the firmware.

Using VIA:
Open the VIA software on your computer and plug in the keyboard.
VIA will detect the keyboard and let you change the layout and test keys.

Using QMK Toolbox:
Open QMK Toolbox, select the firmware file (hex or uf2), press the reset button on the PCB and click Flash.
Wait until the software confirms it is finished.

Step 4: Testing

Use VIA or an online keyboard tester to press every key and make sure each one registers.
If you installed a rotary encoder, rotate and press it to confirm it works.
If RGB is supported on your board, test the lighting modes.

Step 5: Final Assembly

Place the PCB inside the keyboard case.
Install the screws gently and avoid tightening them too hard.
Add all of your keycaps.
Plug the keyboard in one final time and make sure everything works.

Files Included in the Project

The project includes KiCad files for the PCB design, a Gerber zip for manufacturing, firmware files for VIA or QMK and an optional VIA configuration file.

completed yaayyyyyyy huryyyyy!!
