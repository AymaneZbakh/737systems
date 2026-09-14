---
tags:
  - B737
  - flaps
  - leading-edge
  - krueger
  - slats
  - LE
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# LE Devices (Leading Edge Flaps & Slats)
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> 2 Krueger flaps inboard + 4 slats outboard of each engine (12 devices total). Sequenced by the FSEU based on FLAP lever position. Powered by Hyd B; alternate extension via standby hydraulic.

---

## Layout (per wing)

| Device | Location | Count | Position |
|--------|----------|-------|---------|
| Krueger flaps | Inboard of each engine | 2 | One extended position only |
| Slats | Outboard of each engine | 4 | Extended (sealed) or Full Extended (slotted) |

---

## Slat Positions

| Slat State | Leading Edge Shape | When |
|-----------|-------------------|------|
| Retracted | Flush with wing | Flaps UP |
| **Extended** | Sealed leading edge | TE flaps 1°–25° (SFP) / 1°–5° (NON-SFP) |
| **Full Extended** | Slotted leading edge | TE flaps 30°–40° (SFP) / 10°–40° (NON-SFP) |

> [!info]
> Slat position depends on TE flap setting and aircraft type (SFP vs NON-SFP).

---

## Sequencing

- FLAP lever → FSEU → LE devices extend progressively as TE flaps extend
- LE devices receive **hydraulic priority** over TE flaps (priority valve in Flap Control Unit)
- Fully retract **only when FLAP lever is at UP**

---

## LE FLAPS TRANSIT Light (Amber)

> [!warning]
> Any LE device is:
> - In transit (not at commanded position), OR
> - Not in the programmed position relative to TE flaps, OR
> - Two or more LE flaps/slats have moved away from commanded position (uncommanded motion), OR
> - During alternate flap operation: until LE flaps/slats are fully extended AND TE flaps read 10° (15° on SFP)

## LE FLAPS EXT Light (Green)

> [!check]
> LE devices are at the extended position — normal during approach/landing.

---

## Related
- [[FSEU Protection]]
- [[Alternate Extension]]
- [[Autoslats]]
- [[Flight controls/Quick-Reference/Warning Lights]]
