# Krux Thermal Printer Enclosure

A 3D-printed enclosure for the **Goojprt Qr203 58mm thermal printer**. Designed in FreeCAD for use with [Krux](https://github.com/selfcustody/krux) running on K210 modules, but compatible with any application that uses this printer.

The printer ships barebones with no mounting base — this design provides a sturdy enclosure with integrated cable management.

---

## Design Files

| File | Format | Description |
|------|--------|-------------|
| `Enclosure.FCStd` | FreeCAD | Source file for the standard enclosure |
| `Enclosure_CableHole.FCStd` | FreeCAD | Source file for the cable-hole variant |
| `Enclosure-Body.3mf` | 3MF | Ready-to-print standard enclosure |
| `Enclosure_CableHole-Body.3mf` | 3MF | Ready-to-print with cable hole |
| `ThermalPrinter-Print.3mf` | 3MF | Full thermal printer assembly |

Two enclosure variants are provided:
- **Standard** — clean enclosure with a small slot for TTL cable connection
- **Cable hole** — includes an additional hole for the power plug

---

## Hardware Requirements

- [Goojprt Qr203 58mm thermal printer](https://www.aliexpress.com/item/1005005979403268.html)
- [DC power jack](https://www.aliexpress.com/item/33024078552.html) (for the power plug hole variant)
- M3 × 18mm countersunk screws
- TTL cable for data connection

---

## Printing

Load the `.3mf` file of your choice into your preferred slicer and print as-is. No special supports or settings are required.

---

## Wiring & Setup

For wiring the thermal printer to a K210 module running Krux, refer to the official Krux discussion:

- [Thermal Printer — Krux Discussion #312](https://github.com/selfcustody/krux/discussions/312)

---

## License

This work is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue)](https://creativecommons.org/licenses/by-sa/4.0/)
