# blower-command-board

HERE LIES our attempt to resurrect the MedTronic PB560 Ventilator which has been provisionally open-sourced by that company to help with the COVID-19 pandemic.

This repository specicially covers the blower command board (RB0505 / 4096600 E00 001). For other boards see the Ventinow organization.

This board appears to:

- Accept 24VDC, filter, master switch using MOSFETS, produce unregulated 24VDC, and (linear) regulated 15VDC. *Thank you Luciano Aguerre for analysis.*
- Accept brushless motor driver commands.
- Drive a brushless motor through MOSFET half-bridges.

The initial BOM suggests that there is only one obsolete component, FL1, a power-input common-mode filter module. Luciano Aguerre reports that BNX002-11 is a pin and spec-compatible replacement.

*Table of contents:*

### Extracted BOM

Manually generated Bill Of Materials from scanned schematic (first information release).

### Original Gerbers

Gerber files as found in second information release. Renders are by Advanced Circuits FreeDFM service. *Note that gerbv 2.6A had problems rendering these files. Other viewer suggestions welcome.*
