
RP2040 Nano
========================

Compact 4-layer RP2040 development board designed for embedded experimentation, modular integration, and practical prototyping.

[Insert Front Render]

Designed by MRFIRE5673

GitHub:
github.com/MRFIRE5673

------------------------------------------------------------


OVERVIEW & FEATURES
========================

1. Overview

RP2040 Nano is a compact RP2040-based development board designed for embedded experimentation, compact projects, and modular hardware integration.

The board integrates USB-C connectivity, external QSPI flash, EEPROM support, configurable DIP switches, onboard power regulation, and castellated GPIO breakout support in a compact 24.5mm × 25.5mm form factor.

2. Features

• RP2040 dual-core Arm Cortex-M0+ microcontroller
• USB-C connectivity
• External QSPI flash
• EEPROM support
• BOOTSEL button
• WS2812B-2020 RGB status LED
• ME6211 LDO regulator
• 4-position DIP switch
• Polyfuse protection
• 12MHz crystal oscillator
• Castellated GPIO breakout support
• Compact 4-layer PCB design

------------------------------------------------------------


BOARD SPECIFICATIONS
========================

3. Board Specifications

| Parameter             | Value                          |
|----------------------|--------------------------------|
| MCU                  | RP2040                         |
| CPU Core             | Dual Cortex-M0+                |
| USB Interface        | USB-C                          |
| PCB Layers           | 4                              |
| Board Dimensions     | 24.5mm × 25.5mm               |
| Logic Voltage        | 3.3V                           |
| Crystal Frequency    | 12MHz                          |
| Regulator            | ME6211                         |
| Status LED           | WS2812B-2020 RGB LED           |
| GPIO Access          | Castellated breakout           |
| Flash Storage        | External QSPI Flash            |
| EEPROM               | Supported                      |
| Protection           | Polyfuse                       |

------------------------------------------------------------


 ELECTRICAL INFORMATION
========================

4. Absolute Maximum Ratings

| Parameter             | Min  | Max  | Unit |
|----------------------|------|------|------|
| Input Voltage        | -0.3 | 5.5  | V    |
| GPIO Voltage         | -0.3 | 3.3  | V    |
| Storage Temperature  | -40  | 85   | °C   |

5. Recommended Operating Conditions

| Parameter            | Typical Value |
|---------------------|---------------|
| Input Voltage       | 5V            |
| Logic Voltage       | 3.3V          |
| Operating Temp      | 0–70°C        |

------------------------------------------------------------


POWER SYSTEM
========================

6. Power Architecture

The board is powered through USB-C input and regulated using the onboard ME6211 LDO regulator.

A polyfuse is included for input protection.

Power Path

USB-C → Polyfuse → ME6211 → 3.3V Rail

7. Functional Description

• RP2040 acts as the primary processing unit
• External QSPI flash stores firmware and user applications
• EEPROM provides additional non-volatile storage
• WS2812B RGB LED is available for status indication
• BOOTSEL button enables USB bootloader mode
• DIP switches allow configurable hardware behavior

------------------------------------------------------------


 PINOUT & GPIO
========================

8. GPIO Expansion

GPIO access is exposed through castellated edge connections for daughterboard integration and embedded applications.

[Insert Pinout Diagram]

9. GPIO Notes

• GPIO voltage level is 3.3V
• RP2040 alternate functions depend on firmware configuration
• Castellated edges support modular board integration

------------------------------------------------------------


 PCB LAYOUT
========================

10. PCB Layout

Front PCB Render

[Insert Front_render.png]

Back PCB Render

[Insert Back_render.png]

Manufactured PCB

[Insert Pcb_photo.png]

------------------------------------------------------------


 SCHEMATIC & MECHANICAL
========================

11. Schematic Preview

[Insert schematic.png]

12. Mechanical Dimensions

| Parameter         | Value            |
|------------------|------------------|
| Board Width      | 24.5mm           |
| Board Height     | 25.5mm           |
| PCB Layers       | 4                |

------------------------------------------------------------


REVISION HISTORY
========================

13. Current Status

• PCB manufactured
• Rev1 completed
• Assembly/testing pending
• Future revisions planned

14. Revision History

| Revision | Description      |
|----------|------------------|
| Rev1.0   | Initial release  |

------------------------------------------------------------


 NOTES & DISCLAIMER
========================

15. Notes

This board was designed while learning KiCad and experimenting with compact embedded system design.

16. Disclaimer

RP2040 Nano is experimental hardware intended for development, educational, and prototyping purposes.

17. Support & Resources

GitHub:
github.com/MRFIRE5673

Designed by:
MRFIRE5673
