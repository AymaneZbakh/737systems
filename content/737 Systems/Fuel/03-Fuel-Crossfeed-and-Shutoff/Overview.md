---
tags: [fuel, crossfeed, shutoff, overview]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../02-Fuel-Pumps-and-Suction-Feed/Overview|← Previous]] | [[../04-Fuel-Quantity-Indication/Overview|Next →]]

# 🎮 03 — Fuel Crossfeed & Shutoff Valves

> [!abstract] Overview
> The crossfeed valve connects the left and right fuel manifolds so either engine can draw from any tank. Shutoff valves — spar, engine, and APU — isolate fuel at the fire-switch / start-lever level, backed by a dedicated Fuel Shutoff Battery.

## 🎮 Crossfeed Valve

| Parameter | Value |
|---|---|
| Type | Butterfly valve |
| Actuation | DC motor |
| Power source | Battery (BAT) Bus |
| Function | Connects L/R fuel manifolds — either engine can use fuel from any tank |
| Selector CLOSED | Isolates engine No.1 and No.2 fuel feed lines |
| Selector OPEN | Connects engine No.1 and No.2 fuel feed lines |

```
         ┌───────────────┐        ┌───────────────┐
 TANK 1  │  ENGINE No.1  │        │  ENGINE No.2  │  TANK 2
  ───────┤   FEED LINE   ├───────►│   FEED LINE   ├───────
         └───────┬───────┘  X-FEED └───────┬───────┘
                  │          VALVE          │
                  └───────────[⊗]───────────┘
                    (butterfly, DC motor, BAT BUS)
```

> [!warning] Progressive Imbalance
> Continued crossfeed use results in **progressive fuel imbalance**. If the valve fails **open**, imbalance may still occur from slightly different pump outputs — maintain balance via selective pump use per the QRH. If it fails **closed** with both engines running, vary thrust (as conditions allow) to maintain balance.

> [!warning] Unannunciated Leak-Masking Risk
> A known technical issue can leave the crossfeed valve **not fully closed** (unannunciated) — fuel can migrate between tanks. The crossfeed should **NOT** be opened immediately after an in-flight shutdown, as doing so may mask a potential fuel leak. Always follow the FCOM Supplementary Procedure when balancing fuel.

## 🔒 Shutoff Valves Summary

| Valve | Actuation | Power Source(s) | Closes When |
|---|---|---|---|
| [[Components/Spar-Fuel-Shutoff-Valve\|Spar Fuel Shutoff Valve]] | DC motor | HOT BAT BUS (primary) + Fuel Shutoff Battery (backup) | Fire switch pulled / start lever CUTOFF |
| [[Components/Engine-Fuel-Shutoff-Valve\|Engine Fuel Shutoff Valve]] | Fuel-actuated, solenoid controlled | BAT BUS | Fire switch pulled / start lever CUTOFF |
| [[Components/APU-Fuel-Shutoff-Valve\|APU Fuel Shutoff Valve]] | — | HOT BAT BUS (primary) + Fuel Shutoff Battery (backup) | APU fire handle / shutoff command |

> [!note] Both spar AND engine shutoff valves close together whenever the respective **engine fire switch is pulled** or the **engine start lever is placed to CUTOFF**.

## 🧭 Components in This Section

| Page | Summary |
|---|---|
| [[Components/Crossfeed-Valve\|Crossfeed Valve]] | Valve type, light logic, selector |
| [[Components/Spar-Fuel-Shutoff-Valve\|Spar Fuel Shutoff Valve]] | Location, power, closing logic |
| [[Components/Engine-Fuel-Shutoff-Valve\|Engine Fuel Shutoff Valve]] | HPSOV, EEC bypass, Fuel Metering Valve |
| [[Components/APU-Fuel-Shutoff-Valve\|APU Fuel Shutoff Valve]] | Location, power sources |
| [[Components/Fuel-Shutoff-Battery\|Fuel Shutoff Battery]] | Backup power guaranteeing valve closure |

> [!info] Related
> Fuel quantity alerts referencing crossfeed/shutoff states live in [[../04-Fuel-Quantity-Indication/Overview|04 — Fuel Quantity Indication]].
