# RP2040-Zero-Kicad Thru-Hole Footprint
Thru-hole Footprints for the Waveshare [RP2040 Zero dev board](https://www.waveshare.com/wiki/RP2040-Zero).

These footprints do not utilize the castellated pads. Not for paste and reflow.

MCU module is mounted by header pins or small wires. Solder by hand or by wave.

![RP2040-Zero Pinout](images/RP2040-Zero-details.jpg)

## Original footprint: RP2040-Zero.kicad_mod
- 0.8mm holes
- compact pads
- Tight courtyard (perimeter)

## Alternate footprint: RP2040-Zero_1mm.kicad_mod
- 1.0mm holes for square pins
- Larger pads for hand soldering
- Courtyard from physical dimensions
- Solder mask expansion for PCB fab

## ****************************

## Install
- Download the footprint and symbol files.
- Put the files somewhere they can live long-term.

### Symbols
- Open KiCad
- Click `Preferences` -> `Manage Symbol Libraries`
- Select `Global Libraries` and then `+`.
![KiCad Manage Symbol Libraries Screen](images/kicad_screenshot.png)
- Enter `RP2040-Zero` as Nickname.
- Enter the path to the downloaded `RP2040-Zero.kicad_sym` library as Library Path.

### Footprint
- Click `Preferences` -> `Manage Footprint Libraries`
- Select `Global Libraries` and then `+`.
- Enter `RP2040-Zero` as Nickname.
- Enter the path to the downloaded `RP2040-Zero.pretty` library as Library Path.
