- [Repository Information](#org1f07ae5)
  - [Description](#org2590c44)
- [Images](#org2c4b3dd)
- [Schematic](#org33a2bf6)
- [Gerbers](#org8ee03e6)
- [Bill of Materials](#org64941e8)
  - [PCB Parts](#orgdbe567e)
  - [Supplemental Parts](#orgebf0d6d)
  - [Vendor Parts Lists](#org55f5add)
- [Supplemental Documentation](#org219f3eb)
  - [Assembly Instructions](#org5e3c94f)
- [Manufacturing Archive](#org6d19f5f)



<a id="org1f07ae5"></a>

# Repository Information

-   **Name:** y\_arena\_valve\_controller
-   **Version:** 1.2
-   **License:** Open-Source Hardware
-   **URL:** <https://github.com/janelia-kicad/y_arena_valve_controller>
-   **Author:** Peter Polidoro
-   **Email:** peterpolidoro@gmail.com


<a id="org2590c44"></a>

## Description

This board controls the y-arena valves for the Turner lab.


<a id="org2c4b3dd"></a>

# Images


<a id="org33a2bf6"></a>

# Schematic

[./schematic/y\_arena\_valve\_controller.pdf](./schematic/y_arena_valve_controller.pdf)

![img](./schematic/images/schematic00.png)

![img](./schematic/images/schematic01.png)

![img](./schematic/images/schematic02.png)

![img](./schematic/images/schematic03.png)

![img](./schematic/images/schematic04.png)

![img](./schematic/images/schematic05.png)

![img](./schematic/images/schematic06.png)

![img](./schematic/images/schematic07.png)

![img](./schematic/images/schematic08.png)

![img](./schematic/images/schematic09.png)


<a id="org8ee03e6"></a>

# Gerbers

![img](./gerbers/images/gerbers00.png)

![img](./gerbers/images/gerbers01.png)


<a id="org64941e8"></a>

# Bill of Materials


<a id="orgdbe567e"></a>

## PCB Parts

| Item | Reference(s)                        | Quantity | Manufacturer                    | Manufacturer Part Number | Vendor   | Vendor Part Number   | Description                    | Package            |
|---- |----------------------------------- |-------- |------------------------------- |------------------------ |-------- |-------------------- |------------------------------ |------------------ |
| 1    | C1                                  | 1        | TDK Corporation                 | C2012X5R1V106K085AC      | Digi-Key | 445-14417-1-ND       | CAP CER 10UF 35V X5R           | 0805 (2012 Metric) |
| 2    | C10 C12 C14 C16 C18 C2 C4 C6 C8     | 9        | Vishay Sprague                  | 298D105X0016K2T          | Digi-Key | 718-1618-1-ND        | CAP TANT 1UF 20% 16V           | 0402               |
| 3    | C11 C13 C15 C17 C19 C3 C5 C7 C9     | 9        | Murata Electronics              | GCM155R71H153JA55D       | Digi-Key | 490-16428-1-ND       | CAP CER 0.015UF 50V X7R 0402   | 0402               |
| 4    | D1                                  | 1        | Nexperia USA Inc.               | PMEG045V100EPDZ          | Digi-Key | 1727-1904-1-ND       | DIODE SCHOTTKY 45V 10A         | CFP15              |
| 5    | D10 D12 D14 D16 D18 D20 D4 D6 D8    | 9        | Comchip Technology              | CDBQR0230L               | Digi-Key | 641-1275-1-ND        | DIODE SCHOTTKY 30V 200MA       | 0402               |
| 6    | D11 D13 D15 D17 D19 D3 D5 D7 D9 D2  | 10       | Diodes Incorporated             | BAS116LPH4-7B            | Digi-Key | BAS116LPH4-7BDICT-ND | DIODE GEN PURP 85V 215MA 2DFN  | 0402               |
| 7    | L1 L10 L2 L3 L4 L5 L6 L7 L8 L9      | 10       | Lite-On Inc.                    | LTST-C170GKT             | Digi-Key | 160-1179-1-ND        | LED GREEN CLEAR SMD            | 0805 (2012 Metric) |
| 8    | P1                                  | 1        | CUI Devices                     | PJ-036AH-SMT-TR          | Digi-Key | CP-036AHPJCT-ND      | CONN PWR JACK 2X5.5MM SOLDER   |                    |
| 9    | R1 R11 R14 R17 R2 R20 R23 R26 R5 R8 | 10       | Panasonic Electronic Components | ERJ-PA2J391X             | Digi-Key | P124568CT-ND         | RES SMD 390 OHM 5% 1/5W        | 0402               |
| 10   | R10 R13 R16 R19 R22 R25 R28 R4 R7   | 9        | Panasonic Electronic Components | ERJ-2RKF2053X            | Digi-Key | P205KLCT-ND          | RES SMD 205K OHM 1% 1/10W 0402 | 0402               |
| 11   | R12 R15 R18 R21 R24 R27 R3 R6 R9    | 9        | Panasonic Electronic Components | ERJ-2RKF1503X            | Digi-Key | P150KLCT-ND          | RES SMD 150K OHM 1% 1/10W 0402 | 0402               |
| 12   | S1 S2 S3 S4 S5 S6 S7 S8 S9 TEENSY1  | 46       | Mill-Max Manufacturing Corp     | 0305-0-15-15-47-27-10-0  | Digi-Key | ED90331-ND           | CONN PIN RCPT .025-.037 SOLDER |                    |
| 13   | SW1                                 | 1        | E-Switch                        | 500ASSP1SM6QE            | Digi-Key | EG5810CT-ND          | SWITCH SLIDE SPDT 3A 120V      |                    |
| 14   | U1 U2 U3 U4 U5 U6 U7 U8 U9          | 9        | Texas Instruments               | DRV103U                  | Digi-Key | 296-11622-ND         | IC LO-SIDE DRIVER PWM 8SOIC    | 8SOIC              |
|      | FID1 FID2 FID3 FID4 MH1 MH2 MH3     | 7        |                                 |                          |          |                      |                                |                    |


<a id="orgebf0d6d"></a>

## Supplemental Parts

| Item | Quantity | Manufacturer                 | Manufacturer Part Number        | Vendor   | Vendor Part Number                 | Description                      |
|---- |-------- |---------------------------- |------------------------------- |-------- |---------------------------------- |-------------------------------- |
| 1    | 1        | SparkFun Electronics         | DEV-15583                       | Digi-Key | 1568-DEV-15583-ND                  | TEENSY 4.0                       |
| 2    | 1        | Qualtek                      | 3021075-03                      | Digi-Key | Q1223-ND                           | USB 2.0 A MALE TO USB 2.0 MICRO  |
| 3    | 1        | Tripp Lite                   | U222-004-R                      | Digi-Key | TL430-ND                           | HUB USB 4-PORT 2.0 & 1.1         |
| 4    | 1        | MEAN WELL USA Inc.           | GST60A12-P1J                    | Digi-Key | 1866-2149-ND                       | AC/DC DESKTOP ADAPTER 12V 60W    |
| 5    | 1        | MEAN WELL USA Inc.           | YP12+YC12                       | Digi-Key | 1866-5006-ND                       | CORD IEC 320-C13 6FT BLACK       |
| 6    | 1        | Tensility International Corp | 10-02739                        | Digi-Key | 839-1474-ND                        | SPLITTER 5.5X2.1MM F TO X4 M     |
| 7    | 1        | Tensility International Corp | CA-2219                         | Digi-Key | CP-2219-ND                         | CABLE ASSY 5.5X2.1MM M/F R/A 3FT |
| 8    | 1        | Raspberry Pi                 | RASPBERRY PI 4B/4GB             | Digi-Key | 1690-RASPBERRYPI4B/4GB-ND          | RASPBERRY PI 4B/4GB              |
| 9    | 1        | Raspberry Pi                 | RPI USB-C POWER SUPPLY BLACK US | Digi-Key | 1690-RPIUSB-CPOWERSUPPLYBLACKUS-ND | RPI USB-C POWER SUPPLY BLACK US  |
| 10   | 1        | Raspberry Pi                 | RASPBERRY PI 4 CASE BLACK/GREY  | Digi-Key | 1690-RASPBERRYPI4CASEBLACK/GREY-ND | RASPBERRY PI 4 CASE BLACK/GREY   |
| 11   | 1        | Raspberry Pi                 | 8997466                         | Digi-Key | 1690-1007-ND                       | RASPBERRY PI 7" TOUCH SCREEN LCD |
| 12   | 1        | ATP Electronics Inc          | AF32GUD3-OEM                    | Digi-Key | AF32GUD3-OEM-ND                    | MEM CARD MICROSD 32GB CLS 10 MLC |
| 13   | 1        | Tripp Lite                   | U352-000-MD                     | Digi-Key | TL825-ND                           | USB 3.0 MULTI-DRIVE SD CF MS     |
| 14   | 1        | Tripp Lite                   | U336-000-R                      | Digi-Key | TL824-ND                           | USB 3.0 TO ETHERNET ADAPTER      |
| 15   | 1        | Assmann WSW Components       | A-MCSSP60010/B                  | Digi-Key | AE10190-ND                         | CABLE MOD 8P8C PLUG-PLUG 3.28FT  |


<a id="org55f5add"></a>

## Vendor Parts Lists

[./bom/Digi-Key\_parts.csv](./bom/Digi-Key_parts.csv)

[./bom/supplemental\_Digi-Key\_parts.csv](./bom/supplemental_Digi-Key_parts.csv)


<a id="org219f3eb"></a>

# Supplemental Documentation


<a id="org5e3c94f"></a>

## Assembly Instructions

-   Solder surface mount and through hole components onto the pcb.


<a id="org6d19f5f"></a>

# Manufacturing Archive

Send manufacturing zip file to your favorite PCB manufacturer for fabrication.

[./manufacturing/y\_arena\_valve\_controller\_v1.2.zip](./manufacturing/y_arena_valve_controller_v1.2.zip)
