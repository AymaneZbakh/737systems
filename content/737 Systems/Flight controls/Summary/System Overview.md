---
tags: [B737, flight-controls, summary, overview]
---

# System Overview
🔗 [[Home - Flight controls]]

> [!info] Document Reference
> Chapter 9 — Flight Controls | D6-27370-8B6-RAM(B6) | Rev 62 | 30 March 2025
> Combined with CBT course material (RAM B6 training programme)

---

## Primary Controls

| Axis | Surface | Power | Backup | Manual Reversion |
|------|---------|-------|--------|-----------------|
| Roll | [[Ailerons\|Ailerons]] + [[Flight Spoilers\|Spoilers]] | Hyd A or B | Transfer mechanism | Yes — 3° dead band |
| Pitch | [[Elevators\|Elevators]] + [[Stabilizer and Trim\|Stabiliser]] | Hyd A or B | Column breakout | Yes — 1° dead band |
| Yaw | [[Rudder (RSEP)\|Rudder]] | Hyd A + B | Standby hyd | No — needs hyd power |

> [!note] Manual Reversion — Roll and Pitch
> With total hydraulic failure, ailerons and elevator can be controlled mechanically (no power steering).
> Control forces are higher due to friction and aerodynamic loads.
> **Rudder needs hydraulic power (A, B, or STBY) to operate.**

---

## Secondary Controls

| System | Normal Power | Alternate | Key Protection |
|--------|-------------|-----------|---------------|
| [[TE Flaps\|TE Flaps]] | Hyd B | Electric motor | FSEU: skew, asymmetry, uncommanded |
| [[LE Devices\|LE Devices]] | Hyd B | Standby hyd | FSEU: uncommanded motion |
| [[Autoslats\|Autoslats]] | Hyd B | PTU → Hyd B | AUTO SLAT FAIL |
| [[Speed Brakes\|Speed Brakes]] | Hyd A + B | — | Ground Spoiler Interlock Valve |

---

## Automation & Protection Systems

| System | Function | Computers |
|--------|----------|-----------|
| [[Yaw Damper]] | Dutch roll, gust damping, turn coordination (2–3°) | SMYD 1 + 2 |
| [[WTRIS]] | Turn coordination during manual reversion | SMYD + STBY YD |
| [[Mach Trim]] | Prevents Mach tuck above Mach 0.615; FCNSE on T/O | FCC → Mach Trim Actuator |
| [[Speed Trim System\|STS]] | Speed stability at low weight/aft CG/high thrust | FCC A (normally) |
| [[Stall Identification (EFS)\|EFS]] | Increases column forces 4× approaching stall | SMYD → EFS Module |
| [[Autoslats]] | Extends slats to FULL EXT before stickshaker | SMYD |
| [[Flap Load Relief]] | Retracts TE flaps if overspeed | FSEU + Left ADIRU |
| [[Auto Speed Brakes]] | Auto-deploys spoilers on landing/RTO | Auto Speedbrake Module |
| [[Standby Rudder and FFM\|FFM]] | Detects A vs B actuator force fight → standby rudder | Mechanical pressure sensing |
| [[FSEU Protection\|FSEU]] | Asymmetry, skew, uncommanded motion protection | FSEU computer |

---

## Hydraulic Package Architecture

> [!info] Flight Control Hydraulic Packages
> - Two packages: one for Hyd A, one for Hyd B
> - Located in **front section of main wheel well**
> - Control and monitor hydraulic pressure to primary flight controls and flight spoilers
> - LOW PRESSURE light illuminates when sensed pressure < 1,300 psi
> - Will NOT illuminate when FLT CONTROL switch is in STBY RUD and standby shutoff valve is open
> - Some aircraft: compensator cartridge maintains 40–70 psi when depressurised (gust protection)

---

## Key Interconnections

```
CPT wheel ─── Aileron Input Shaft ─── Aileron PCUs ─── Ailerons
            └── (via Transfer Mechanism cables) ──────────────────┐
F/O wheel ─── Spoiler Control Shaft ── Spoiler Mixer ─── Flight Spoilers
                                     └── Ground Spoiler Control Valve
                                           └── Ground Spoiler Interlock Valve (MLG WOW)
                                                 └── Ground Spoilers

CPT/F/O column ─── Elevator Cables ─── AFT Quadrant ─── Torque Tube ─── Elevator PCUs ─── Elevators
A/P ─────────────── A/P Input Crank ──────────────────────────────────┘

Rudder pedals ─── FWD Quadrant ─── Bus Rod ─── Cables ─── AFT Quadrant ─── Torque Tube ─── Main PCU (A+B) ─── Rudder
                                                                                          └── Standby PCU (STBY)
SMYD (Yaw Damper) ────────────────────────────────────────────────────────────────────────────┘
```
