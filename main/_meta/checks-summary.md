## KiCad 10 ERC & DRC Report — `Board_alex`

> [!CAUTION]
> **🚨 2 KiCad ERROR(S) DETECTED (2 ERC, 0 DRC)** — The pipeline continued without blocking so artifacts remain available. **Do not manufacture before reviewing!**

- **KiCad Version:** `10.0.8`
- **Gate Policy:** Non-blocking — errors are highlighted via alerts & GitHub annotations without stopping the build.

| Check | Status | Errors | Warnings | Exclusions |
| :--- | :---: | :---: | :---: | :---: |
| **ERC** (`Board_alex.kicad_sch`) | 🚨 **2 ERROR(S)** | **2** | 124 | 0 |
| **DRC** (`Board_alex.kicad_pcb`) | ✅ PASS | **0** | 80 | 0 |
| ↳ PCB Rules | — | 0 | 63 | — |
| ↳ Unconnected Items | — | 0 | 0 | — |
| ↳ Schematic Parity | — | 0 | 17 | — |

<details><summary>❌ ERC Errors by Category</summary>

- `power_pin_not_driven`: **2**

1. **`power_pin_not_driven`** [/]: Input Power pin not driven by any Output Power pins (Symbol #PWR01 Pin 1 [Power input, Line] @ (38.10, 190.50 mm))
2. **`power_pin_not_driven`** [/]: Input Power pin not driven by any Output Power pins (Symbol #PWR05 Pin 1 [Power input, Line] @ (73.66, 191.77 mm))

</details>

<details><summary>⚠️ ERC Warnings</summary>

- `lib_symbol_issues`: **75**
- `footprint_link_issues`: **49**

1. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Button_Switch_SMD' (Symbol SW1 [SW_Push] @ (13.97, 58.42 mm))
2. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Switch' (Symbol SW1 [SW_Push] @ (13.97, 58.42 mm))
3. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Connector_PinHeader_2.54mm' (Symbol J2 [Conn_01x05_Pin] @ (15.24, 24.13 mm))
4. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Connector' (Symbol J2 [Conn_01x05_Pin] @ (15.24, 24.13 mm))
5. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'power' (Symbol #PWR015 [+3.3V] @ (17.78, 107.95 mm))
6. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Capacitor_SMD' (Symbol C9 [C] @ (17.78, 111.76 mm))
7. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Device' (Symbol C9 [C] @ (17.78, 111.76 mm))
8. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'power' (Symbol #PWR014 [GND] @ (17.78, 115.57 mm))
9. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Resistor_SMD' (Symbol R3 [R] @ (17.78, 176.53 mm))
10. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Device' (Symbol R3 [R] @ (17.78, 176.53 mm))
11. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Capacitor_SMD' (Symbol C14 [C] @ (25.40, 57.15 mm))
12. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Device' (Symbol C14 [C] @ (25.40, 57.15 mm))
13. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Capacitor_SMD' (Symbol C1 [C] @ (25.40, 176.53 mm))
14. **`lib_symbol_issues`** [/]: The current configuration does not include the symbol library 'Device' (Symbol C1 [C] @ (25.40, 176.53 mm))
15. **`footprint_link_issues`** [/]: The current configuration does not include the footprint library 'Connector_USB' (Symbol J1 [USB_C_Receptacle_USB2.0_16P] @ (26.67, 146.05 mm))

_...and 109 more (see full JSON report artifact)._

</details>

<details><summary>⚠️ DRC Warnings</summary>

- `lib_footprint_issues`: **53**
- `extra_footprint`: **9**
- `silk_over_copper`: **8**
- `missing_footprint`: **5**
- `duplicate_footprints`: **3**
- `silk_edge_clearance`: **2**

1. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Resistor_SMD' (Footprint R8 @ (125.33, 93.12 mm))
2. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Resistor_SMD' (Footprint R11 @ (120.35, 106.55 mm))
3. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C7 @ (128.10, 103.10 mm))
4. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C15 @ (131.82, 105.45 mm))
5. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'MountingHole' (Footprint REF** @ (134.35, 117.62 mm))
6. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C1 @ (107.05, 111.20 mm))
7. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C3 @ (114.15, 99.55 mm))
8. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C8 @ (115.25, 96.90 mm))
9. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'MountingHole' (Footprint REF** @ (134.35, 88.50 mm))
10. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Resistor_SMD' (Footprint R1 @ (103.40, 98.47 mm))
11. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Package_TO_SOT_SMD' (Footprint U1 @ (107.35, 105.96 mm))
12. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Resistor_SMD' (Footprint R4 @ (111.03, 105.20 mm))
13. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C19 @ (132.60, 106.88 mm))
14. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Resistor_SMD' (Footprint R13 @ (114.83, 106.88 mm))
15. **`lib_footprint_issues`**: The current configuration does not include the footprint library 'Capacitor_SMD' (Footprint C20 @ (134.95, 109.03 mm))

_...and 65 more (see full JSON report artifact)._

</details>
