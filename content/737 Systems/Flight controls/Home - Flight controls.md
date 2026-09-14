---
tags: [B737, FCOM, CBT, flight-controls]
revision: Rev62
date: 2025-03-30
---

 ✈ B737 Flight Controls — Chapter 9
 
> [!info] Document Reference
> FCOM
> Royal Air Maroc — Boeing 737

---
## 🗂 Sections

| #   | System                       | Main Page                          |
| --- | ---------------------------- | ---------------------------------- |
| 1   | Roll Control                 | [[Roll Control]]                   |
| 2   | Pitch Control                | [[Pitch Control]]                  |
| 3   | Yaw Control                  | [[Yaw Control]]                    |
| 4   | Flaps & Slats                | [[Flight controls/04-Flaps-Slats/Flaps and Slats]]                |
| 5   | Speed Brakes                 | [[Speed Brakes]]                   |
| 6   | Pilot Controls & Indications | [[Pilot Controls and Indications]] |

---
## 📋 Summary & Reference

- [[Flight controls/Summary/System Overview]]
- [[Hydraulic Power Sources]]
- [[Key Speeds and Limits]]
- [[Stabilizer Trim Limits]]
- [[Flap Load Relief Speeds]]
- [[Flight controls/Quick-Reference/Warning Lights]]
- [[Component Locations]]

---
## 🧭 System Architecture

```
Flight Controls
├── Primary Controls
│   ├── Roll → Ailerons + Flight Spoilers
│   │   PCUs · Transfer Mech · Spring Cartridge · Lost Motion Device
│   ├── Pitch   → Elevators + Stabiliser
│   │   PCUs · Feel Computer · Mach Trim · STS · EFS · Stab Neutral Shift
│   └── Yaw     → Rudder + Yaw Damper
│       Main PCU · Standby PCU · FFM · WTRIS · SMYD
└── Secondary Controls
    ├── High-Lift → Flaps + Slats
    │   FSEU · Autoslats · Load Relief · Alt Extension
    ├── Drag  → Speed Brakes / Spoilers
    │   Spoiler Mixer · Ground Spoiler Interlock Valve · Auto Module
    └── Inputs  → Cockpit Controls & Indications
```

---
## ⚡ Key Numbers at a Glance

| Parameter                             | Value                             |
| ------------------------------------- | --------------------------------- |
| Rudder load limiter ON                | > 137 kts                         |
| Rudder load limiter OFF               | < 132 kts                         |
| Max rudder travel                     | 29° L/R                           |
| Rudder nose gear steering             | 7°                                |
| Mach trim activates                   | > Mach 0.615                      |
| STS active range                      | 100 KIAS – Mach 0.60              |
| Auto speedbrake spin-up               | > 60 kts                          |
| Flap extension altitude limit         | 20,000 ft                         |
| EFS inhibit (radio altitude)          | < 100 ft                          |
| EFS activates AOA                     | 2.7°–10.2° above stick shaker AOA |
| EFS increases feel forces             | ~4× normal                        |
| Spoiler deflection starts             | Wheel > 10° (= 1.6 trim units)    |
| 1 trim unit = control wheel rotation  | 6°                                |
| 1 stab trim unit                      | ~1° stabiliser movement           |
| 1 stab trim unit = manual wheel turns | ~15 turns                         |
| Lost motion device dead band          | 12° wheel rotation                |
| Manual reversion dead band (aileron)  | 3° wheel                          |
| Manual reversion dead band (pitch)    | 1° column                         |
| Aileron PCU pogos                     | 4× (2 per PCU)                    |
| Stab trim wheels offset               | 90°                               |

