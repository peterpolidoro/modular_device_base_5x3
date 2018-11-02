- [Repository Information](#org3363df3)
  - [Description](#orgd222b12)
- [Images](#orga7265e7)
- [Schematic](#orgfcf2128)
- [Gerbers](#org41eb2be)
- [Bill of Materials](#org5237e5d)
  - [PCB Parts](#org7a5a6dd)
  - [Supplemental Parts](#org5971931)
  - [Vendor Parts Lists](#orgb088364)
- [Supplemental Documentation](#org552370b)
  - [Assembly Instructions](#org9c28d25)



<a id="org3363df3"></a>

# Repository Information

-   **Name:** modular\_device\_base\_5x3
-   **Version:** 1.2
-   **License:** Open-Source Hardware
-   **URL:** <https://github.com/janelia-kicad/modular_device_base_5x3>
-   **Author:** Peter Polidoro
-   **Email:** peterpolidoro@gmail.com


<a id="orgd222b12"></a>

## Description

This board is the base of 5x3 format modular devices. It is a breakout board for the microprocessor, with connections for power, communication, and top boards.


<a id="orga7265e7"></a>

# Images

![img](./images/top.png)

![img](./images/bottom.png)


<a id="orgfcf2128"></a>

# Schematic

[./schematic/modular\_device\_base\_5x3.pdf](./schematic/modular_device_base_5x3.pdf)

![img](./schematic/images/schematic00.png)


<a id="org41eb2be"></a>

# Gerbers

Send gerbers zip file to your favorite PCB manufacturer for fabrication.

[./gerbers/modular\_device\_base\_5x3\_v1.2.zip](./gerbers/modular_device_base_5x3_v1.2.zip)

![img](./gerbers/images/gerbers00.png)

![img](./gerbers/images/gerbers01.png)


<a id="org5237e5d"></a>

# Bill of Materials


<a id="org7a5a6dd"></a>

## PCB Parts

| Item | Reference(s)                         | Quantity | PartNumber          | Vendor  | Description                                           |
|---- |------------------------------------ |-------- |------------------- |------- |----------------------------------------------------- |
| 1    | C1 C2 C3 C4 C5                       | 5        | 445-4536-1-ND       | digikey | CAP CER 10UF 50V 10% X7S 1210                         |
| 2    | C6                                   | 1        | 399-13229-1-ND      | digikey | CAP CER 0.1UF 100V X7R 1210                           |
| 3    | D1 D2                                | 2        | LSM115JE3/TR13CT-ND | digikey | DIODE SCHOTTKY 15V 1A DO214BA                         |
| 4    | D10 D11 D12 D13 D3 D4 D5 D6 D7 D8 D9 | 11       | 568-11697-1-ND      | digikey | DIODE SCHOTTKY 45V 10A CFP15                          |
| 5    | L1                                   | 1        | 350-1712-ND         | digikey | LED 2MM 5V RT ANGLE RED PCMNT                         |
| 6    | L2                                   | 1        | 350-1717-ND         | digikey | LED 2MM 5V RT ANGLE GREEN PCMNT                       |
| 7    | L3                                   | 1        | 350-1719-ND         | digikey | LED 2MM 5V RT ANGLE YELLOW PCMNT                      |
| 8    | MDB1                                 | 2        | S7058-ND            | digikey | 25 Position Header Through Hole Female Socket         |
| 9    | MH1 MH2 MH3 MH4 MH5 MH6 MH7 MH8      | 8        | 36-2027-ND          | digikey | Round Standoff Threaded 4-40 Aluminum 0.500in 0.187in |
| 10   | P1                                   | 1        | CP-063BH-ND         | digikey | CONN PWR JACK DC 2.5X5.5 8A T/H                       |
| 11   | P10 P4 P6 P8                         | 4        | A100903CT-ND        | digikey | CONN HEADER 2POS R/A SMD GOLD                         |
| 12   | P11                                  | 1        | 732-5336-ND         | digikey | CONN HEADER 3 POS RA 2.54                             |
| 13   | P12 P13                              | 2        | SAM10781-ND         | digikey | CONN HEADER 2POS .100in SNGL SMD                      |
| 14   | P2                                   | 1        | ACX1655-ND          | digikey | CONN BNC JACK R/A 75 OHM PCB                          |
| 15   | P3 P5 P7 P9                          | 4        | A100890CT-ND        | digikey | CONN HEADER 3POS R/A SMD GOLD                         |
| 16   | R1                                   | 1        | P6.19KAACT-ND       | digikey | RES SMD 6.19K OHM 1% 1/2W 1210                        |
| 17   | REG1                                 | 1        | 945-1395-5-ND       | digikey | CONV DC/DC 1A 5V OUT SIP VERT                         |
| 18   | SW1 SW2                              | 2        | CKN1860CT-ND        | digikey | SWITCH TACTILE SPST-NO 1VA 32V                        |
| 19   | TEENSY1                              | 1        | 1568-1443-ND        | digikey | TEENSY 3.5                                            |
| 20   | U1                                   | 1        | MAX6817EUT+TCT-ND   | digikey | IC DEBOUNCER SWITCH DUAL SOT23-6                      |


<a id="org5971931"></a>

## Supplemental Parts

| Item | Quantity | PartNumber    | Vendor  | Description                                                              |
|---- |-------- |------------- |------- |------------------------------------------------------------------------ |
| 1    | 1        | 62-1187-ND    | digikey | AC/DC DESKTOP ADAPTER 24V 90W                                            |
| 2    | 1        | 993-1037-ND   | digikey | CORD 3COND NEMA PLUG 320-C5                                              |
| 3    | 2        | A106625CT-ND  | digikey | 14 Positions Header Unshrouded Breakaway Connector 0.100in 2 row SMD     |
| 4    | 3        | S1011EC-24-ND | digikey | 14 Positions Header Unshrouded Breakaway Connector 0.100in 1 row Through |
| 5    | 1        | S9001-ND      | digikey | CONN JUMPER SHORTING GOLD FLASH                                          |
| 6    | 1        | AE10342-ND    | digikey | CABLE USB-A TO MICRO USB-B 2M                                            |
| 7    | 2        | 492-1077-ND   | digikey | ROUND SPACER 4 NYLON 7/16in                                              |


<a id="orgb088364"></a>

## Vendor Parts Lists

[./bom/digikey\_parts.csv](./bom/digikey_parts.csv)

[./bom/supplemental\_digikey\_parts.csv](./bom/supplemental_digikey_parts.csv)


<a id="org552370b"></a>

# Supplemental Documentation


<a id="org9c28d25"></a>

## Assembly Instructions

-   Cut the bottom trace on the Teensy board that connects the 5V pads according to these instructions <https://www.pjrc.com/teensy/external_power.html>.
-   Solder through hole header pins into every Teensy 0.1 inch header hole.
-   Solder surface mount header pins onto the bottom of the Teensy making sure they are properly aligned.
-   Solder surface mount and through hole components onto the pcb.
-   Solder the Teensy into the pcb making sure it is properly aligned.
-   Connect header jumper to RED LED enable pins.
