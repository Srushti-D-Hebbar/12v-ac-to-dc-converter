# 12V AC to DC Converter

A compact two-layer PCB designed in KiCad for converting a 12V AC input into an unregulated DC output using a full-wave bridge rectifier and capacitor filtering. The board also includes an LED power indicator and a bleeder resistor across the DC output.

---
## Overview

The circuit uses four 1N4007 diodes arranged as a full-wave bridge rectifier to convert the AC input into pulsating DC. A 1000µF electrolytic capacitor smooths the rectified waveform, while a 10kΩ bleeder resistor provides a discharge path when the input power is removed. An LED with a current-limiting resistor indicates the presence of the DC output.

The output is **unregulated DC** and its voltage depends on the AC input and load.

---
## Features

- Full-wave bridge rectifier using 4 × 1N4007 diodes
- 1000µF electrolytic smoothing capacitor
- 10kΩ bleeder resistor
- LED power indicator with current-limiting resistor
- Screw-terminal AC input
- Screw-terminal DC output
- Two-layer PCB
- Four mounting holes

---
## Schematic

![Schematic](ac_dc_converter_sch.png)

---
## PCB Design

### Front

![PCB Front](ac_dc_converter_front.png)

### Back

![PCB Back](ac_dc_converter_back.png)

### Front Layout

![Front Layout](ac_dc_converter_layout_front.png)

### Back Layout

![Back Layout](ac_dc_converter_layout_back.png)

---
## PCB Specifications

- **PCB Layers:** 2
- **Board Type:** Through-hole
- **Input:** 12V AC
- **Output:** Unregulated DC
- **Rectifier:** Full-wave bridge
- **Filter:** 1000µF electrolytic capacitor
- **Indicator:** LED
- **Mounting:** 4 × mounting holes

---
## Design Verification

- Schematic completed in KiCad
- PCB layout and routing completed
- **ERC:** 0 errors
- **DRC:** 0 violations
- **Unconnected Items:** 0
- 3D model and PCB visualization verified

---
## Software Used

- KiCad 10

---
## Learning Outcomes

- Schematic capture and electrical connectivity
- Component and footprint selection
- Through-hole PCB layout
- PCB routing and track management
- Electrical Rules Check (ERC)
- Design Rules Check (DRC)
- PCB visualization and 3D inspection
- Understanding of bridge rectification and capacitor-filtered DC supplies

---
## Future Improvements

- Add input fuse and protection
- Add a voltage regulator for a fixed DC output
- Add input and output test points
- Add reverse-polarity/output protection
- Improve terminal block mechanical protection

---
## License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE) file for details.

---
## Author

**Srushti D Hebbar**

[GitHub](https://github.com/Srushti-D-Hebbar)
