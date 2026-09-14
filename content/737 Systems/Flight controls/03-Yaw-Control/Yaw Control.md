---
tags: [B737, flight-controls, yaw, rudder, yaw-damper, WTRIS]
system: Yaw Control
hydraulics: [Hyd-A, Hyd-B, Standby]
---

# ↻ Yaw Control
> [!abstract] Overview
> Single hydraulically-powered rudder (RSEP). Main PCU uses dual independent hydraulic inputs (Hyd A + B). Standby PCU uses standby hydraulics. Load limiter, Force Fight Monitor, and WTRIS provide additional protection and coordination.

🔗 [[Home - Flight controls]] | [[Pitch Control|← Pitch Control]] | [[Flight controls/04-Flaps-Slats/Flaps and Slats|Next: Flaps & Slats →]]

---

## Sub-systems

| System | Page |
|--------|------|
| Rudder (RSEP) | [[Rudder (RSEP)]] |
| Standby Rudder & FFM | [[Standby Rudder and FFM]] |
| Yaw Damper | [[Yaw Damper]] |
| Rudder Trim | [[Rudder Trim]] |
| WTRIS | [[WTRIS]] |

---

## Quick Facts

| Item | Detail |
|------|--------|
| Surface | Single rudder (RSEP) |
| Main PCU | 2 input rods + 2 control valves + 2 actuators |
| Main PCU power | Hyd A + Hyd B (one each) |
| Standby PCU power | Standby hydraulic |
| Aerodynamic effectiveness | 40–60 kts |
| Max rudder travel | 29° L/R |
| Load limiter activates | > 137 kts (~25% pressure reduction) |
| Load limiter restores | < 132 kts |
| Rudder pedal nose gear steering | 7° |
| Yaw damper movement | 2–3° L/R |

---

## Control Path

```
Rudder pedals → cables → Fwd Rudder Quadrants → Bus Rod
             → Rudder Control Cables → Aft Rudder Quadrant
             → Rudder Torque Tube → Rudder Feel & Centring Unit
             → Main Rudder PCU (HYD A + HYD B) → Rudder surface

Standby: Standby HYD PCU → Rudder surface (parallel path)
Yaw Damper: SMYD → Main or Standby PCU (no pedal movement)
```

---

## Manual Reversion

> [!danger]
> The rudder **requires hydraulic power** (A, B, or STBY) to operate.
> Unlike ailerons and elevators, there is **no manual reversion** for the rudder.
> At least one hydraulic system must be available.
