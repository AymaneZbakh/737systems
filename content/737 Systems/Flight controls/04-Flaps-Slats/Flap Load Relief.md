---
tags:
  - B737
  - flaps
  - load-relief
  - overspeed
  - FSEU
  - SFP
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# Flap Load Relief
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> Protects TE flaps from excessive aerodynamic loads by automatically retracting one setting when airspeed exceeds the limit for the selected position. Function provided by the FSEU using Left ADIRU (captain airspeed) data.

---

## SFP vs NON-SFP

| Aircraft | Flap Load Relief Range |
|----------|----------------------|
| **NON-SFP** (737-700 etc.) | Flaps **30° and 40° only** |
| **SFP** (737-800 etc.) | Flaps **10° through 40°** |

---

## Trigger Speeds

| From → To | Retracts above | Re-extends below |
|---|---|---|
| 40° → 30° | 163 kts | 158 kts |
| 30° → 25° | 176 kts | 171 kts |
| 25° → 15° | 191 kts | 186 kts |
| 15° → 10° | 201 kts | 196 kts |
| 10° → 5° | 211 kts | 206 kts |

> [!note] SFP only for 10°–25° rows above

---

## Key Points

- **FLAP lever does NOT move** when load relief activates — monitor flap position indicator
- Uses **Left ADIRU** (captain airspeed) as data source
- Flaps re-extend automatically once speed returns below re-extension threshold
- LE devices remain at their current position during load relief

---

## Related
- [[FSEU Protection]]
- [[TE Flaps]]
- [[Flap Load Relief Speeds]]
