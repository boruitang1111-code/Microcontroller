# Fisher 1
This is my personal microcontroller board for the Hackclub phantom project.
<img width="1286" height="795" alt="image" src="https://github.com/user-attachments/assets/8465a774-d350-407a-ac6f-090cdd50dcc7" />
<img width="1115" height="771" alt="image" src="https://github.com/user-attachments/assets/473270bc-d698-4860-aa65-a578e7f1989a" />
<img width="641" height="499" alt="image" src="https://github.com/user-attachments/assets/3f590963-fc99-4d64-b518-2dcd1a192067" />

This board is powered by a rp2040 microcontroller and was made to tinker with. It exist to do microcontroller things and to power other potential projects. Because of this it has one fully featured gpio pin header and easy access Bootsel and reset button.
The Fisher 1 board features a unified header with dual power and data usb ports. Meaning it has 30gpio pins in one long stretch and 2 different USB port for power and data.

# Assembly guide
1. purchase pcb.
2. purchase parts.
3. solder parts.
4. done.

# How to flash
1. plug data cable into usb-B port
2. hold down bootsel button and click reset button
3. check computer for a removable drive called RPI-RP2
4. put .uf2 file into RPI-RP2

# specs:
IC: rp2040
Storage: W25Q128 (16MB external flash)
GPIO: 30pins
Power:5v USB C
Data:Standard Micro USB

# BOM
| ID | Designator | Footprint | Qty | Value | LCSC part | Unit price |
|----|------------|-----------|-----|-------|-----------|------------|
| 1 | C1, C2, C3, C9, C11, C12, C13, C14, C15, C16, C17 | `C_0603_1608Metric` | 11 | 100nF | [C14663](https://www.lcsc.com/product-detail/C14663.html) | 0.0055 |
| 2 | C4, C5 | `C_0603_1608Metric` | 2 | 15pF | [C1644](https://www.lcsc.com/product-detail/C1644.html) | 0.112 |
| 3 | C6 | `C_0603_1608Metric` | 1 | 10µF | [C19702](https://www.lcsc.com/product-detail/C19702.html) | 0.0169 |
| 4 | C7, C8, C10 | `C_0603_1608Metric` | 3 | 1µF | [C15849](https://www.lcsc.com/product-detail/C15849.html) | 0.0142 |
| 5 | J1 | `USB_C_Receptacle_HRO_TYPE-C-31-M-17` | 1 | USB_C_Receptacle_PowerOnly_6P | [C2765186](https://www.lcsc.com/product-detail/C2765186.html) | 0.0747 |
| 6 | J2 | `USB_Micro-B_Amphenol_10118193-0001LF_Horizontal` | 1 | USB_B_Micro | [C132562](https://www.lcsc.com/product-detail/C132562.html) | 0.2810 |
| 7 | J3 | `PinHeader_1x03_P2.54mm_Vertical` | 1 | Conn_01x03_Pin | [C2937625](https://www.lcsc.com/product-detail/C2937625.html) | 0.0185 |
| 8 | J4, J5 | `PinHeader_1x30_P2.54mm_Vertical` | 2 | Conn_01x30_Pin | [C2883689](https://www.lcsc.com/product-detail/C2883689.html) | 0.4547 |
| 9 | R1, R2 | `R_0603_1608Metric` | 2 | 5.1k | [C23186](https://www.lcsc.com/product-detail/C23186.html) | 0.0015 |
| 10 | R3, R5 | `R_0603_1608Metric` | 2 | 10k | [C25804](https://www.lcsc.com/product-detail/C25804.html) | 0.0017 |
| 11 | R4 | `R_0603_1608Metric` | 1 | 1k | [C21190](https://www.lcsc.com/product-detail/C21190.html) | 0.0016 |
| 12 | reset, SW1 | `SW_SPST_B3U-1000P` | 2 | SW_Push | [C231329](https://www.lcsc.com/product-detail/C231329.html) | 0.1894 |
| 13 | U1 | `QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm` | 1 | RP2040 | [C2040](https://www.lcsc.com/product-detail/C2040.html) | 1.0968 |
| 14 | U2 | `WSON-8-1EP_8x6mm_P1.27mm_EP3.4x4.3mm` | 1 | W25Q128JVE | [C2456297](https://www.lcsc.com/product-detail/C2456297.html) | 4.1214 |
| 15 | U3 | `SOT-23-5` | 1 | AP2112K-3.3 | [C51118](https://www.lcsc.com/product-detail/C51118.html) | 0.1683 |
| 16 | Y1 | `Crystal_SMD_Abracon_ABM8G-4Pin_3.2x2.5mm` | 1 | Crystal_GND24 | [C276421](https://www.lcsc.com/product-detail/C276421.html) | 0.4560 |

# Important clarification:
i have no idea what i am doing and this has not been produced nor tested. Prototype at you own risk.
