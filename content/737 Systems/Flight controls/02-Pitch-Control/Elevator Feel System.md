---
tags: [B737, pitch, feel-system, elevator-feel]
parent: "[[Pitch Control]]"
---

# Elevator Feel System
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Simulates aerodynamic forces on the control column using airspeed (pitot/static) and stabiliser position. Uses the higher of Hyd A or B pressure. The EFS (Elevator Feel Shift) module doubles feel forces during stall approach.

---

## Inputs to Feel Computer

| Input | Source |
|-------|--------|
| Airspeed (dynamic pressure) | Pitot probes on vertical stabiliser |
| Stabiliser position | Stabiliser position sensor (input rod) |
| Hydraulic pressure | Higher of Hyd A or B |

> [!info] Location
> The [[Elevator Feel Computer|Elevator Feel Computer]] is located in the aft fuselage (tail section), with a pitot port and static port visible.

---

## Stabiliser Controlled Neutral Shift

Flight Control Computers and **Elevator Neutral Shift Rods** change the elevator neutral position depending on stabiliser trim setting. Inputs transferred through the **Mach Trim Actuator**.

| Stab trim setting | Effect |
|-------------------|--------|
| 0 – 10.5 units | Elevator **downrigged** ~4° down — reduces pitch force during initial climb |
| 10.5 – 17 units | Downrig gradually changes to **uprig** — decreases stab AOA, reduces risk of stab buffet with ice |

---

## FEEL DIFF PRESS Light (Amber)

> [!warning]
> Illuminates when:
> - Excessive differential pressure exists across the feel system
> - One hydraulic system or pitot probe fails
> - Erroneous EFS module activation
>
> Can cause abnormally high or low column forces. Refer to QRH/NNC.

---

## Related
- [[Elevator Feel Computer]]
- [[Stall Identification (EFS)]]
- [[Mach Trim]]
- [[Flight controls/Quick-Reference/Warning Lights]]
