---
tags: [B737, flight-controls, roll, ailerons, spoilers]
system: Roll Control
hydraulics: [Hyd-A, Hyd-B]
---

# ↔ Roll Control

> [!abstract] Overview
> Hydraulically controlled ailerons and spoilers. Flight deck controls are mechanically linked to hydraulic PCUs which command the primary flight control surfaces. The aileron transfer mechanism allows either pilot to maintain roll control if a jam occurs.

🔗 [[Home - Flight controls]] | [[Pitch Control|Next: Pitch Control →]]

---

## Sub-systems

| Component | Page |
|-----------|------|
| Ailerons & PCUs | [[Ailerons]] |
| Aileron Trim | [[Aileron Trim]] |
| Flight Spoilers | [[Flight Spoilers]] |
| Transfer Mechanism | [[Transfer Mechanism]] |
| **Components** | |
| Aileron Input Shaft | [[Aileron Input Shaft]] |
| Aileron PCU & Pogos | [[Aileron PCU and Pogos]] |
| Aileron Body Quadrants | [[Aileron Body Quadrants]] |
| Aileron Feel & Centering Unit | [[Aileron Feel and Centering Unit]] |
| Aileron Spring Cartridge | [[Aileron Spring Cartridge]] |
| Spoiler Mixer | [[Spoiler Mixer]] |
| Spoiler Control Shaft | [[Spoiler Control Shaft]] |
| Aileron A/P Actuators | [[Aileron AP Actuators]] |
| Control Wheels | [[Control Wheels]] |

---

## Quick Facts

| Item | Detail |
|------|--------|
| Primary surfaces | 2 ailerons (L + R) |
| Supplementary | 8 flight spoilers (4 per wing) |
| Hyd power | Hyd A & B — either sufficient |
| Manual reversion | Available — 3° dead band in roll |
| Spoiler activation threshold | Wheel > 10° (= 1.6 trim units) |
| Spoilers first to extend | Panels 4+5 and 8+9 (inner) |
| Aileron trim | Dual switches → feel & centering unit |
| 1 trim unit | = 6° control wheel rotation |

---

## Hydraulic Power — Roll Surfaces

| Surface | Hyd A | Hyd B |
|---------|:-----:|:-----:|
| Ailerons | ✅ | ✅ |
| Flight spoilers 2, 3, 10, 11 | ✅ | — |
| Flight spoilers 4, 5, 8, 9 | — | ✅ |

---

## Manual Reversion

> [!warning] Manual reversion — roll
> With total hydraulic power failure, ailerons can be controlled mechanically (no power steering).
> - Control forces are **higher** due to friction and aerodynamic loads
> - Input cranks in PCU must hit mechanical stops first → **3° dead band** before movement begins
> - There is **no manual reversion** for flight and ground spoilers
> - [[Aileron PCU and Pogos|PCU pogos]] isolate jams to maintain freedom of movement

---

## Control Path Summary

```
CPT wheel ──→ Aileron Input Shaft ──→ Aileron Feel & Centering Unit ──→ Aileron PCU ──→ Ailerons
F/O wheel ──→ Spoiler Control Shaft ──→ Spoiler Mixer ──→ Spoiler PCUs ──→ Flight Spoilers
            (Both wheels interconnected via Aileron Transfer Mechanism cables)
```
