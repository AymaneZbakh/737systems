---
tags: [B737, yaw, yaw-damper, SMYD, dutch-roll, WTRIS]
parent: "[[Yaw Control]]"
---

# Yaw Damper
🔗 [[Yaw Control|← Yaw Control]]

> [!abstract]
> Dual yaw damper system (main + standby) controlled by SMYD computers receiving ADIRU data and control wheel inputs. Functions: Dutch roll damping, gust damping, turn coordination. Pedals do NOT move.

---

## System Architecture

| Component | Power | Computer | Active when |
|-----------|-------|----------|-------------|
| Main yaw damper | Hyd B | SMYD 1 + 2 | FLT CONTROL switches ON |
| Standby yaw damper | Standby hyd | SMYD 1 + 2 | Both FLT CONTROL switches in STBY RUD |

---

## SMYD Inputs

| Input | Source |
|-------|--------|
| ADIRU data | Roll rate, yaw rate, heading |
| Control wheel position | CPT control wheel position sensor |
| Yaw Damper switch | ON/OFF |

---

## Functions

| Function | Description | Authority |
|----------|-------------|-----------|
| Dutch roll prevention | Damps oscillatory yaw/roll coupling | 2–3° L/R |
| Gust damping | Reduces yaw disturbances in turbulence | 2–3° L/R |
| Turn coordination | Reduces adverse yaw during roll inputs | 2–3° L/R |

> [!info] Pedals do NOT move
> Yaw damper inputs move the rudder but do **not** back-drive the rudder pedals.
> Monitor on MFD SYS page (RUDDER indicator shows yaw damper inputs separately).

---

## Stall — SMYD Behaviour

- At **high AOA**: SMYD computers **reduce yaw damper rudder movement** to prevent adverse yaw effects near stall

---

## YAW DAMPER Light (Amber)

> [!warning]
> Yaw damper not engaged. Possible Dutch roll tendency — especially at altitude and high speed.
> Engage via YAW DAMPER switch. Refer to QRH if fails to engage.

---

## Related
- [[WTRIS]]
- [[Rudder (RSEP)]]
- [[Stall Identification (EFS)]]
- [[Flight controls/Quick-Reference/Warning Lights]]
