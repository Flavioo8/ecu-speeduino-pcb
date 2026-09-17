# ecu-speeduino-pcb

PCB for an ECU (engine control unit) based on the open-source [Speeduino](https://github.com/speeduino/speeduino) project, designed in Proteus around an Arduino MEGA. The board was manufactured and tested on a Chevrolet 1.6L engine.

## Why I built it
To strengthen my understanding of how an ECU manages an engine (sensor reading, fuel injection and ignition control) and to learn the electronics behind it.

## What I learned across 18 revisions
Not everything that can be designed can be built that easily:
- **Trace width:** adjusted to the limits of the laser machine used to manufacture the PCB.
- **Routing:** only routing that can actually be manufactured is useful.
- **Component placement:** placing each component correctly changes the whole design.

## Contents
- `proteus/revisiones/`: revisions 1 to 18.1 of the schematic and PCB (`revNN_` shows the order).
- `proteus/esquematicos/` and `proteus/simulaciones/`: base schematics and injector/ignition coil control simulations.
- `gerber/`: CADCAM files for versions 14 and 18.1. `pcb-pdf/`: TOP, BOTTOM and SILK layers.
- `bom/`: bill of materials with the actual components. `docs/`: minimum required connections (pinout).

Firmware is not included: the board runs unmodified Speeduino, available in its official repository.
