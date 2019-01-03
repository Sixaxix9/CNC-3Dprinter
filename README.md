# CNC-3Dprinter

In this repository I have uploaded all the material related to a fresh design of a machine capable of working various type of materials, including wood and aluminum, with the nice addition of an extruder to use it as a 3D printer.

# Electronics
I have uploaded the Eagle project of the board. Below you can find a list of all the important feautures and the distinctive sign of this board. I also have uploaded the Gerber files for printing a PCB, in case you would like to power your 3D printer or CNC with my hardware.

# Distintive signs
* **5 independant stepper motor drivers**: Three of them are usually assigned to the cartesian axes X, Y, Z while the other two can be used for a 4 or 5 axes CNC, or to drive up to two extruders.
* **4 high current PWM outputs**: I have included four low-side switches for tool/extruder/general purpose driving. With a selector you can redirect up to two digital pins to power MOSFETs. I have placed the footprint of a low-power MOS in SOT-23 (intended to drive low demanding loads like a fan) and of a high power MOS in D2Pack. The user can choose which to solder relying on the purpose.
* **Endstops** Three endsotps are ibcluded in the board with anti-debouncing RC filters. Up two pins can be redirected
