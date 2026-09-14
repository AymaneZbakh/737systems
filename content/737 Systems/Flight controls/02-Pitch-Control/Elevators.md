---
tags: [B737, pitch, elevators, PCU, torque-tube]
parent: "[[Pitch Control]]"
---

# Elevators
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Pitch control around the lateral axis. Two elevators interconnected by a torque tube. Left PCU powered by Hyd A, right by Hyd B. Manual reversion available with 1° dead band.

---

## Control Path

```
Control column → Elevator Control Cables
              → [[02-Pitch-Control/Components/Elevator Aft Control Quadrant|Elevator Aft Control Quadrant]]
              → Input Torque Tube
              → [[02-Pitch-Control/Components/Elevator PCU|Elevator PCUs]] (Left: HYD A / Right: HYD B)
              → Elevator surface
```

- Both columns interconnected by a **torque tube** (fwd input torque tube)
- **Elevator breakout mechanism** allows columns to separate if one is jammed

---

## Power Control Units

| PCU | Hydraulic | Location |
|-----|-----------|----------|
| Left PCU | Hyd A | Aft fuselage |
| Right PCU | Hyd B | Aft fuselage |

- Each PCU receives commands from the **input torque tube** through **input pogos**
- Pogo function: allows operation even after a jam downstream of the pogo
- If a pogo jams: approximately **14 kg additional column force** required to move elevator to commanded position
- PCU supplies hydraulic pressure to the actuator, which moves the elevator

---

## Breakout Mechanism (Jam)

> [!important]
> If one control column is jammed, the **elevator breakout mechanism** allows the other column to move independently.
> - Reduced elevator travel available after breakout
> - Sufficient for approach and landing flare

---

## Autopilot

- A/P mechanically moves the elevator input torque tube through the **[[AP Actuator Input Crank|A/P Actuator Input Crank]]**

---

## Manual Reversion

- Column must be displaced > **1°** (dead band) before mechanical stops engage
- PCU housing then moves — driving elevator to commanded position
- **Balance panels** on elevator move opposite to elevator deflection — reduces aerodynamic hinge moment and required column forces

---

## Related
- [[Elevator Aft Control Quadrant]]
- [[02-Pitch-Control/Components/Elevator PCU]]
- [[AP Actuator Input Crank]]
- [[Elevator Feel System]]
- [[Flight controls/02-Pitch-Control/Elevator Tab Control System]]
