---
title: "Split-Steno-Qwerty-KeyBoard"
author: "Vinay N"
description: "Split & Modular keyboard that can be used for Stenography and QWERTY"
created_at: "2026-05-11"
---

# May 12

Spent time relearning how to use kicad and sourcing information and schematic/pcb footprints. designed the first half of one side of the split & modular keyboard. 

![schematics](day1.png)
Total time spent: 56 Minutes

# Jun 4
Had to rewrite the Schematics as during the first run the same input gpio buttons were also connected to the same gpio output which would result in 9 keys where 3 keys would be unique with 3 buttons per key. 2nd I was able to add space for an 8 pin magnetic connector on the pcb for the modular part of the keyboard as i wanted the keyboard to be one version for steno and an enitrely different on based on the StenoKeyboards Uni V4 and Polyglot. I made the left half of the pcb then made a second one reversed to create 2 halves of the keyboard. I also sourced the magnetic 8 prong connectors in order to figure out if it should be included in the PCB or whether I need to find a new solution.
![Schematics](Day2Schem.png)
![PCB Right Hand SIde](Day2PCBR.png)
![PCB Left Hand SIde](Day2PCBL.png)
Total time spent: 79 Minutes
