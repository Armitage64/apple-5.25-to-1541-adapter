# apple-5.25-to-1541-adapter
A PCB that allow the use of an Apple 5.25" ALPS drive in a Commodore 1541

## Purpose
Commodore 1541 disk drives with Mitsumi/Newtronics mechanisms are known to suffer from failed read/write heads effectively rendering the drives useless and un-repairable. It is possible to replace the Newtronics drive with an Alps drive from another 1541, or from an Apple 5.25" drive model A9M0107 (and possibly others).

This adapter PCB will allow you to connect the Alps drive from an Apple 5.25" drive directly to the 1541 controller board without cutting or splicing any wires.

This video demonstrates the process: https://youtu.be/947pPsSaGOQ

## Specifications
* Base Material: FR-4
* Layers: 2
* PCB Thickness: 1.6mm
* Dimension: 75 mm x 20 mm
* Outer Copper Weight: 1 oz

## Bill of Materials
* 2.54mm male and female pin headers

## Important Notes
* When converting a Newtronics 1541 to Alps, you must cut jumper J6 on the controller board per the service manual.
  
* Only certain 1541s have the above jumper. PCB Assy # 250442-01 and 250446-01 do according to the service manual. Later models may as well, including the 251830 Rev A that I used. Assy # 1540008-01 and 1540048-01 are ALPS-only, 1540048-03 is Newtronics-only.

* Within the same revision Apple 5.25 drive models, the wiring can be different. This adapter assumes CN1-19 is Yellow and CN1-20 is Brown. If your drive has Orange and Black instead, you can re-pin your connector before using this adapter. If you do not, the drive will still function but the stepper motor may be off by half a step causing the drive to misread Track 1 on the first attempt.

<img width="930" height="295" alt="pcb_back" src="https://github.com/user-attachments/assets/d007d989-c419-4781-9e18-753cfc9051bf" />
<img width="865" height="312" alt="pcb_front" src="https://github.com/user-attachments/assets/cdb59920-28cf-414a-997e-66aee4801168" />

RetroBits on YouTube - https://youtube.com/retrobitstv
