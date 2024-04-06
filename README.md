Dev board for STM32F103C8T6 using Altium. 
![image](https://github.com/haris-mujeeb/STM32_Blue_Pill/assets/57053470/8761b4e2-45a7-4672-9102-fdf19b9724ec)
![image](https://github.com/haris-mujeeb/STM32_Blue_Pill/assets/57053470/21f17723-61de-4bc1-96d4-f423a5b1942e)

All components are sourced from JLCPCB Parts Library (extended parts).

## Bill of Material:
| Component                         | Description                                                                             | Designator                                        | Footprint                           | LibRef                           | Quantity |
| ------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------- | ----------------------------------- | -------------------------------- | -------- |
| Capacitor 4.7µF +/-40% 25V 0805 | Chip Capacitor, 4.7µF +/-40%, 25V, 0805, Thickness 1.45 mm                              | C1, C2, C3, C4, C5, C6, C7, C8, C9, C10, C11, C12 | CAPC0805(2012)145_L                 | CMP-001-00080-4, CMP-001-00080-5 | 12       |
| Power Supply                    | LED GREEN CLEAR CHIP SMD                                                                | D1                                                | LED 0805_2012 GREEN                 | APHCM2012CGCK-F01                | 1        |
| Test                            | LED RED CLEAR SMD                                                                       | D2                                                | LED 0805_2012 RED                   | LTST-C170KAKT                    | 1        |
| Zener 3V3                       | DIODE ZENER 3.3V 410MW SOD123                                                           | D3                                                | SOD-123                             | BZT52C3V3-HE3-18                 | 1        |
| STM32F103C8T6XXX                | Integrated Circuit                                                                      | IC1                                               | QFP50P900X900X160-48N               | STM32F103C8T6XXX                 | 1        |
| 2-826646-0                      | CONN HEADER VERT 20POS 2.54MM                                                           | J1, J2                                            | FP-2-826646-0-MFG                   | CMP-03369-000139-1               | 2        |
| 2x3P                            | PZ254-2-03-Z-8.5                                                                        | J3                                                | 2x3P 2.54mm Pin Header -Footprint-1 | CMP-002-00390-1                  | 1        |
| M20-9960445                     | CONN HEADER R/A 4POS 2.54MM                                                             | J4                                                | HARWIN M20-9960445                  | M20-9960445                      | 1        |
| MICROXNJ USB 2.0                | 1A USB 2.0 1 Surface Mount 5P Female -20℃~+85℃ Micro-B SMD USB Connectors ROHS         | J5                                                | USB 2.0 Tupe B Micro                | CMP-002-00071-9                  | 1        |
| 470R5J                          | 470R 0.125W 5% 0805 (2012 Metric) SMD                                                   | R1, R2, R3, R4, R5, R6, R7, R8                    | RESC0805(2012)_L                    | CMP-009-00102-2, CMP-009-00102-3 | 8        |
| TS-1088-AR02016                 | NO 50mA 100MΩ 100000 Times 12V 160gf@±50gf Brick nogging SPST SMD Tactile Switches ROHS | S1                                                | TS-1088-AR02016-Footprint-1         | CMP-011-00069-3                  | 1        |
| XC6206P332MR                    | 200mA Fixed 3.3V Positive 6V SOT-23-3L Linear Voltage Regulators (LDO) ROHS             | U1                                                | XC6206P332MR-Footprint-1            | CMP-019-00049-3                  | 1        |
| MC-30632.7680K-A0:ROHS          | 32.768 kHz ±20ppm Crystal 12.5pF 50 kOhms 4-SOJ, 5.50mm pitch                           | Y1                                                | MC-30632.7680K-A0:ROHS-Footprint-1  | CMP-003-00031-7                  | 1        |
| X50328MSB2GI                    | 8MHz 20pF ±10ppm SMD5032-2P Crystals ROHS                                               | Y2                                                | X50328MSB2GI-Footprint-1            | CMP-003-00032-3                  | 1        |

## Errors to fix: 
- The silk screen clearances need to be fixed.
