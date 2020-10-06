# Arty A7 Root Repository

## Arty A7-100 XADC Demo

### Description

This branch contains sources for the Arty A7-100 XADC Demo.

This project is a Vivado demo using the Arty A7-100T analog-to-digital converter ciruitry,switches and LEDs, written in Verilog. When programmed onto the board, voltage levels between 0 and 1 Volt are read off of the JXADC header.  
The 6 User LEDs increment from top right to left then bottom right to left as the voltage difference on the selected XADC pins gets larger. A0-A5 are single ended analog pins while A6-A7, A8-A9, and A10-A11 are differential ports. Each XADC channel can be selected depending on the switches position as shown in the following table.  

| Channel Pin/s  | SW3    | SW2   | SW1   | SW0   |
| -------------- | -------| ------| ------| ------| 
| A0             | Down   | Down  | Down  | Down  |
| A1             | Down   | Down  | Down  | Up    |
| A2             | Down   | Down  | Up    | Down  |
| A3             | Down   | Down  | Up    | Up    |
| A4             | Down   | Up    | Down  | Down  |
| A5             | Down   | Up    | Down  | Up    |
| A6-A7          | Down   | Up    | Up    | Down  |
| A8-A9          | Down   | Up    | Up    | Up    |
| A10-A11        | Up     | Down  | Down  | Down  |
| V_P-V_N        | Up     | Down  | Down  | Up    |
  
For more information on the Arty A7-100 XADC Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/demos/xadc) on the Digilent Wiki.

For more information on the Arty A7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Arty-A7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes          |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Arty-A7-100-XADC/

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Arty A7-100T
* Vivado 2020.1 Installation
* MicroUSB cable
* Wires and a circuit to measure