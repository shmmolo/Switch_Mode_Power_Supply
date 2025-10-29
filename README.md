# 25 W @ 9 V Flyback SMPS Charger with USB-PD

A compact isolated Flyback SMPS delivering 25 W power for USB-C PD fast charging, designed around TI’s UCC28750 controller.

## Features
- 220 VAC input → 9 V / 5 V output
- USB-PD communication via IP2721
- UCC28750 PWM controller + optocoupler feedback
- Schottky rectification and snubber protection
- 2-layer PCB with ground plane and isolation gap

## Components
- **U1:** UCC28750 Flyback Controller  
- **Q1:** NMOS primary switch  
- **U2:** PC817 Optocoupler  
- **U3:** TL431 Voltage Reference  
- **U4:** IP2721 USB-PD Controller  
- **D1–D5:** GBU4K + SS310 Schottky diodes  
- **T1:** Flyback Transformer (custom)  
- **C1–C12:** Filtering capacitors

## Output Specs
| Mode | Voltage | Current | Power |
|------|----------|----------|--------|
| Default | 5 V | 2.8 A | 14 W |
| USB-PD | 9 V | 2.8 A | 25 W |

## Notes
PCB under layout stage – final design will feature 2-layer structure with dedicated GND plane, thermal reliefs, and isolation.
