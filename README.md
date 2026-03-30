# Arnav-AGV-Embedded-PCB-nPM110-
AIM:
This project involves the design of a 4-layer PCB using KiCad for the nPM1100 Power Management IC.The schematic is created based on the reference configuration provided in the datasheet, and the PCB layout is developed with proper component placement, grounding, and routing techniques.


FEATURES OF MODEL:
Battery charging and power management
4-layer PCB design
Ground plane implementation


SOFTWARE USED:
KiCad EDA


FILES INCLUDED:
Npm1100.kicad_sch → Schematic
Npm1100.kicad_pcb → PCB Layout
Npm1100.pdf → Schematic PDF
pcb.pdf → PCB PDF


SOME APPROACHES:
Followed datasheet reference design given.
Used In1.Cu as GND plane and In2.Cu as power plane to connect VBUS,VSYS and VBAT.
Routed power signals (VBUS, VBAT, VSYS) using tracks in In2.Cu.
Added vias to connect GND pads to ground plane.
Tried to place capacitors and inductor near the centre.
Used PCB calculator to get trace width.
Added LED to ERR and CHG to get indications.
Added connector 1x2 header pin to get input.


AUTHOR:
Arnav Pandey
