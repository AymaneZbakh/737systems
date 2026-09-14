---
tags: [B737MAX, MAX-8, anti-ice, TAI, WAI, core-anti-ice, icing-idle]
system: Anti-Ice
---

# 🧊 MAX-8 Anti-Ice
🔗 [[Home - MAX Differences]] | [[Air Systems|← Air Systems]] | [[Engines|Next: Engines →]]

> [!abstract] Overview
> The anti-ice indication in the flight deck has been redesigned. The MAX adds a new **Core Anti-Ice** system, a new **Icing Idle** regime, and redesigned cockpit lights to replace the NG's COWL VALVE OPEN / L/R VALVE OPEN lights.

---

## Overhead Panel Changes

| NG Light | MAX Light | Function |
|----------|-----------|---------|
| COWL VALVE OPEN | **COWL VALVE** | Engine cowl anti-ice valve status |
| L/R VALVE OPEN | **L/R VALVE** | Wing anti-ice valve status |
| (new) | **ENG ANTI-ICE** | Engine anti-ice system failure |

---

## COWL VALVE Lights (Engine Anti-Ice — TAI)

- Indicate operation of the cowl valve for **engine anti-ice (TAI)**
- The light illuminates when:
  - Cowl valve is **in transit** → COWL VALVE illuminates momentarily
  - Cowl valve **position disagrees** with the switch → COWL VALVE illuminates steady → after 6 seconds triggers **MASTER CAUTION**

---

## L/R VALVE Lights (Wing Anti-Ice — WAI)

- Indicate operation of the valves for **wing anti-ice (WAI)**
- Light is **inhibited** with take-off thrust set (60° TRA)
- The light illuminates when:
  - Wing anti-ice valve is **in transit** → L/R VALVE illuminates momentarily
  - Wing anti-ice valve **position disagrees** with the switch → L/R VALVE illuminates steady → after 6 seconds triggers **MASTER CAUTION**

---

## ENG ANTI-ICE Light

Illuminates when:
- Engine anti-ice system has a failure and the TAI is inhibited
- Engine **core anti-ice valve fails closed**

---

## Icing Idle (New on MAX)

> [!note] New idle regime — highest idle
> In addition to ground idle, approach idle, and flight idle, the 737 MAX features a new **Icing Idle** (the highest idle setting).

**Activation**: When engine anti-ice is ON, flaps up, and gear up:

| Altitude | EEC Action |
|----------|-----------|
| Below 22,000 ft | Transfer to **Full Icing Idle** |
| Above 30,400 ft | Stay in **Minimum Flight Idle** |
| Between 22,000 ft and 30,400 ft | Gradually transfer between flight idle and icing idle depending on altitude |

---

## Core Anti-Ice (New on MAX)

> [!info] Automatic core anti-ice — no crew action
> - LEAP-1B features a new core anti-ice system
> - Operation is **automatically managed by the EEC** — no crew switch
> - Provides automatic ice protection for the engine core using hot air from the **7th stage of the High-Pressure Compressor (HPC)** and **Variable Bleed Valves (VBV)**

---

## Quick Reference — Anti-Ice Panel

```
ENGINE ANTI-ICE PANEL (AFT OVERHEAD)
┌─────────────────────────────────────────────────────────┐
│              ENG ANTI-ICE    ENG ANTI-ICE               │
│              COWL ANTI-ICE   COWL ANTI-ICE              │
│  L VALVE   R VALVE   COWL VALVE  COWL VALVE            │
│         WING ANTI-ICE              ENG ANTI-ICE         │
│              OFF                      OFF               │
│              ON                       ON                │
└─────────────────────────────────────────────────────────┘
```

---

## Related
- [[Air Systems]] — bleed air source for anti-ice
- [[Engines]] — EEC manages core anti-ice
- [[Flight controls/Quick-Reference/Warning Lights]]
