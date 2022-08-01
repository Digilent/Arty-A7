# Arty A7 Root Repository

## Arty A7-100 GPIO Demo

### Description

This branch contains sources for the Arty A7-100 GPIO Demo.

This project is a Vivado demo using the Arty A7's Switches, LEDs, RGB LED's, Pushbuttons, and USB UART bridge, written in VHDL. When programmed onto the board, the switches are tied to the LEDs.  
Every time a switch is pushed on, the corresponding LED will light up. The RGB LED smoothly transitions between colors.  
On reset, the Arty A7-100 sends the line “ARTY GPIO/UART DEMO!” to the serial terminal. Whenever one of the buttons is pressed, the line “Button press detected!” is sent.

For more information on the Arty A7-100 GPIO Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/demos/gpio) on the Digilent Wiki.

For more information on the Arty A7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Arty-A7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes |
| OS        | No |
| SW        | No |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Arty-A7-100-GPIO/

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Arty A7-100T
* Vivado 2022.1 Installation
* Serial Terminal
* MicroUSB Cable
