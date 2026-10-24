# CH32Duino
A Devboard made from an ultra cheap ch32v203

## Features
- Arduino micro-ish pinout
- USB-C Port
- Ultra-cheap (parts < 10$)

## Why?
I finished making a full scale arduino-esque board and I wanted to make another devboard. I chose to make one as cheap as I Could. I probably could have skimped even more on the usb socket and LDO, but I went with ones I knew about.

## BOM

| Qty | Reference | Value | Package | Description | Price | Link |
|---:|---|---|---|---|---:|---|
| 1 | U1 | CH32V203C8T6 | LQFP-48 (7 × 7 mm) | Main MCU | $0.8821 | [JLCPCB](https://jlcpcb.com/partdetail/WCH_Jiangsu_Qin_Heng-CH32V203C8T6/C3001172) |
| 1 | U2 | AMS1117-3.3 | SOT-223 | LDO, +5V to +3.3V | $0.2048 | [JLCPCB](https://jlcpcb.com/partdetail/Advanced_MonolithicSystems-AMS1117_33/C6186) |
| 1 | U3 | USB-C Receptacle | SMD | USB-C Port | $0.1869 | [JLCPCB](https://jlcpcb.com/partdetail/Korean_HropartsElec-TYPE_C_31_M12/C165948) |
| 2 | R1, R2 | 10K | 0805 | 10K 0805 Resistors | $0.0034 | [JLCPCB](https://jlcpcb.com/partdetail/18102-0805W8F1002T5E/C17414) |
| 2 | R3, R4 | 5.1K | 0805 | 5.1K 0805 Resistors | $0.0055 | [JLCPCB](https://jlcpcb.com/partdetail/28584-0805W8F5101T5E/C27834) |
| 2 | C1, C2 | 100nF | 0805 | 100nF 0805 Capacitors | $0.0205 | [JLCPCB](https://jlcpcb.com/partdetail/YAGEO-CC0805KRX7R9BB104/C49678) |
| 1 |  | | | PARTS SUBTOTAL (with minimum quantities): | $6.7640 |

## Firmware
For firmware, I am using ch32fun at the moment.
