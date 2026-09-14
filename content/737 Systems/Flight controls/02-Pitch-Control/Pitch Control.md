---
tags: [B737, flight-controls, pitch, elevators, stabiliser]
system: Pitch Control
hydraulics: [Hyd-A, Hyd-B]
---

# ↕ Pitch Control

> [!abstract] Overview
> Two hydraulically-powered elevators interconnected by a torque tube, plus an electrically-powered horizontal stabiliser. Multiple automation layers: Mach Trim, Speed Trim System (STS), Elevator Feel Shift (EFS), and Stabiliser Controlled Neutral Shift.

🔗 [[Home - Flight controls]] | [[Roll Control|← Roll Control]] | [[Yaw Control|Next: Yaw Control →]]

---

## Sub-systems

| System | Page |
|--------|------|
| Elevators | [[Elevators]] |
| Elevator Feel System | [[Elevator Feel System]] |
| Elevator Tab Control System | [[Flight controls/02-Pitch-Control/Elevator Tab Control System]] |
| Stabiliser & Trim | [[Stabilizer and Trim]] |
| Mach Trim | [[Mach Trim]] |
| Speed Trim System (STS) | [[Speed Trim System]] |
| Stall Identification (EFS) | [[Stall Identification (EFS)]] |
| **Components** | |
| Elevator Aft Control Quadrant | [[Elevator Aft Control Quadrant]] |
| Elevator PCU | [[02-Pitch-Control/Components/Elevator PCU]] |
| A/P Actuator Input Crank | [[AP Actuator Input Crank]] |
| Elevator Feel Computer | [[Elevator Feel Computer]] |
| Stabiliser Alignment Tabs | [[Stabiliser Alignment Tabs]] |

---

## Quick Facts

| Item | Detail |
|------|--------|
| Primary surfaces | 2 elevators (interconnected by torque tube) |
| Secondary | Horizontal stabiliser (electric) |
| Left PCU power | Hyd A |
| Right PCU power | Hyd B |
| Manual reversion | Available — 1° dead band in pitch |
| Mach trim activates | > Mach 0.615 |
| STS range | 100 KIAS – Mach 0.60 |
| Stab trim 1 unit | ≈ 1° stabiliser movement |
| Stab trim 1 unit manual | ≈ 15 turns of trim wheel |
| Stab trim wheels offset | 90° |
| Transfer Bus #2 | Required for electric trim |

---

## Stabiliser Trim Limits

| Mode | Min | Max | Speed |
|------|-----|-----|-------|
| Main electric + A/P — flaps NOT up (HIGH) | 0.05 | 14.5 | 0.4 / 0.27 units/sec |
| Main electric + A/P — flaps UP (SLOW) | 3.95 | 14.5 | 0.2 / 0.09 units/sec |
| Manual trim | -0.2 | 16.9 | — |

---

## Control Path Summary

```
Control column → Elevator Control Cables
              → Elevator Aft Control Quadrant → Input Torque Tube
              → Elevator PCUs (Left: HYD A / Right: HYD B)
              → Elevator surface

A/P → A/P Actuator Input Crank → Input Torque Tube → PCUs → Elevator

Stab Trim Switches / A/P → Stab Trim Actuator → Gearbox → Jackscrew → Stabiliser
Manual → Trim Wheels → Manual Trim Wheel Cables → Aft Cable Drum → Gearbox → Jackscrew
```

---

## Manual Reversion

> [!warning]
> With total hydraulic failure, elevators can be controlled mechanically.
> - **1° dead band** before input cranks hit mechanical stops
> - Higher control forces due to friction and aerodynamic loads
> - Elevator **balance panels** move opposite to elevator deflection — reduces required column forces
> - Two independent brake systems engage when stabiliser is not being trimmed
