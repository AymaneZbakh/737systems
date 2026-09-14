---
tags: [B737, yaw, WTRIS, manual-reversion, turn-coordination]
parent: "[[Yaw Control]]"
---

# WTRIS — Wheel-to-Rudder Interconnect System
🔗 [[Yaw Control|← Yaw Control]]

> [!abstract]
> WTRIS is a function of the Standby Yaw Damper. It uses the CPT's control wheel position sensor to command small rudder inputs for better turn coordination during manual reversion.

---

## Purpose

- Improves **turn coordination** during **manual reversion** (when hydraulics have failed and ailerons/elevators are operated mechanically)
- Without yaw damper inputs, adverse yaw during roll would be uncompensated
- WTRIS uses the standby rudder PCU to provide coordinated rudder during turns

---

## System Requirements (ALL must be met)

| Requirement | Condition |
|-------------|-----------|
| FLT CONTROL switch A | STBY RUD position |
| FLT CONTROL switch B | STBY RUD position |
| Yaw Damper switch | ON |

> [!note]
> WTRIS uses the **Standby Yaw Damper**, **Standby HYD system**, and **Standby Rudder PCU**.

---

## Signal Path

```
CPT control wheel position sensor
  → SMYD computers
  → Standby Yaw Damper channel
  → Standby Rudder PCU
  → Small rudder deflection for turn coordination
```

---

## Related
- [[Yaw Damper]]
- [[Standby Rudder and FFM]]
- [[Rudder (RSEP)]]
