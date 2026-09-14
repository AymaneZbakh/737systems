---
tags: [B737, flight-controls, speed-brakes, spoilers, ground-spoilers]
system: Speed Brakes
hydraulics: [Hyd-A, Hyd-B]
---

# ◼ Speed Brakes
> [!abstract] Overview
> Flight spoilers (4+4) serve as in-flight speed brakes. Ground spoilers (2+2) deploy on ground only. The Spoiler Mixer combines roll and speedbrake inputs. Automatic deployment on landing via the Auto Speedbrake Module. Ground Spoiler Interlock Valve prevents inadvertent ground spoiler deployment in flight.

🔗 [[Home - Flight controls]] | [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]] | [[Pilot Controls and Indications|Next: Pilot Controls →]]

---

## Sub-systems

| System | Page |
|--------|------|
| Speed Brake Lever | [[Speed Brake Lever]] |
| In-Flight Operation | [[In-Flight Operation]] |
| Auto Speed Brakes | [[Auto Speed Brakes]] |
| **Components** | |
| Spoiler Mixer | [[Spoiler Mixer]] |
| Ground Spoiler Control Valve | [[Ground Spoiler Control Valve]] |
| Ground Spoiler Interlock Valve | [[Ground Spoiler Interlock Valve]] |
| Push-Pull Cable | [[Push-Pull Cable]] |
| Auto Speedbrake Module | [[Auto Speedbrake Module]] |

---

## Spoiler Panel Summary

| Panels | Type | Hydraulic | Deploys |
|--------|------|-----------|---------|
| 1, 6 | Ground spoiler (left) | Hyd A | Ground only |
| 2, 3 | Flight spoiler (left) | Hyd A | Flight + Ground |
| 4, 5 | Flight spoiler (left) | Hyd B | Flight + Ground |
| 7, 12 | Ground spoiler (right) | Hyd A | Ground only |
| 8, 9 | Flight spoiler (right) | Hyd B | Flight + Ground |
| 10, 11 | Flight spoiler (right) | Hyd A | Flight + Ground |

> [!info] Ground spoilers — deploy condition
> Ground spoilers deploy **only on ground** (right main landing gear strut compressed).
> Ground spoilers move > **31°** when speedbrake lever moves beyond 31°.

---

## Speed Brake Lever Positions

| Position | Effect |
|----------|--------|
| **DOWN** (detent) | All panels faired |
| **ARMED** | Auto system armed; lever auto-advances to UP on touchdown |
| **50%** (selected a/c) | Load alleviation retract point |
| **FLIGHT DETENT** | All flight spoilers at max — **in-flight limit** |
| **UP** | All flight + ground spoilers — **ground use only** |

> [!note] SFP — Lever stop
> On SFP (Scimitar Fence Performance) aircraft: when flaps are up, a **lever stop** limits movement between DOWN and FLIGHT DETENT in flight.

---

## Ground Spoiler Deployment Logic

```
Speedbrake lever beyond FLIGHT DETENT
  → Spoiler Mixer mechanical link
  → Ground Spoiler Control Valve (opens)
  → Hyd A pressure to Ground Spoiler Interlock Valve
  → If weight on RIGHT MLG (push-pull cable)
    → Ground Spoiler Interlock Valve OPENS
    → Hyd A flows to Ground Spoiler Actuators → Deploy
```
