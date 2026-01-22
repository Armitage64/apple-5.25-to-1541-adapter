# apple-5.25-to-1541-adapter
A PCB that allow the use of an Apple 5.25"/UniDisk ALPS drive in a Commodore 1541

## Purpose
Commodore 1541 disk drives with Mitsumi/Newtronics mechanisms are known to suffer from failed read/write heads effectively rendering the drives useless and un-repairable. It is possible to replace the Newtronics drive with an Alps drive from another 1541, or from an Apple 5.25" (UniDisk) drive model A9M0107 (and possibly others).

This adapter PCB will allow you to connect the Alps drive from an Apple 5.25" (UniDisk) drive directly to the 1541 controller board without cutting or splicing any wires.

This YouTube video demonstrates the process: tbd

## Specifications

* Base Material: FR-4
* Layers: 2
* PCB Thickness: 1.6mm
* Dimension: 75 mm x 20 mm
* Outer Copper Weight: 1 oz

### Important Notes
* When converting a Newtronics 1541 to Alps, you must cut jumper J6 on the controller board per the service manual.

* Within the same revision Apple 5.25 drive models, the wiring can be different. This adapter assumes CN1-19 is Yellow and CN1-20 is Brown. If your drive has Orange and Black instead, you can re-pin your connector before using this adapter. If you do not, the drive will still function but the stepper motor may be off by half a step causing the drive to misread Track 1 on the first attempt.

RetroBits on YouTube - https://youtube.com/retrobitstv
