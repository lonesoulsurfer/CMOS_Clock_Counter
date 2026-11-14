# CMOS Clock Counter

This clock counts seconds, from 0 to 99,999 (1.15 days), then it starts again at 0. It is a visual reminder of the seconds that go past. It uses only CMOS logic ICs and 7-segment displays.

![CMOS Clock Counter](https://github.com/user-attachments/assets/1e5e45ff-ed89-4309-9bb1-3d80a0cc427b)

## Build guide and video

- Step-by-step build guide on Instructables: [CMOS Counter Clock](https://www.instructables.com/CMOS-Counter-Clock/)
- Video on YouTube: [CMOS Clock Counter build](https://www.youtube.com/watch?v=ALrcwJxQYL8)

## How it works

- A 4060 binary counter with a crystal oscillator makes an accurate pulse every second.
- This pulse is the clock input for a chain of 4033 decade counters. Each 4033 drives one 7-segment display.
- You can connect as many 4033 ICs in a chain as you want. In theory, you could make a "googol clock" (1 followed by 100 zeros).
- Red transparent acrylic on the front diffuses the light of the displays.

## Two versions

| Version | Power | Folder |
|---------|-------|--------|
| 5 V USB-C | 5 V from a USB-C cable | `CMOS Clock - 5V USB-C Version/` |
| Battery | 9 V battery (not tested) | `CMOS Clock - Battery Version/` |

Each folder has the Eagle files, the schematic and the Gerber files for that version.

## What you need

- All parts are in the [parts list](CMOS%20Clock%20-%20Parts%20List%20(PDF).pdf).

## Build it

The Instructables guide shows each step, with photos. In short:

1. Send the Gerber files to a PCB maker.
2. Get the parts in the parts list.
3. Solder the parts to the PCB.
4. Put the red acrylic over the displays.
5. Connect the power and test the circuit.

![CMOS Clock Counter build](https://github.com/user-attachments/assets/5ecac74b-ba1e-46a8-9963-a78da28d2065)

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `CMOS Clock - 5V USB-C Version/` | Eagle files, schematic and Gerber files for the USB-C version |
| `CMOS Clock - Battery Version/` | Eagle files, schematic and Gerber files for the battery version |
| `CMOS Clock - Parts List (PDF).pdf` | Parts list |

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

This project uses the [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0). Copyright (c) 2024 Marcus (lonesoulsurfer).

You can make, change and sell boards from these files. If you share or sell a changed design, you must also share the changed design files under the same licence.
