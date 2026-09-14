---
tags: [fuel, storage, feed, overview]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[Home]] | [[02-Fuel-Pumps-and-Suction-Feed/Overview|Next →]]

# ⛽ 01 — Fuel Storage & Feed

> [!abstract] Overview
> Three fuel tanks (two main, one center) supply the engines and APU. Center tank fuel is used first; check valves throughout the system prevent uncommanded fuel transfer between tanks.

## 🛢 Fuel Tanks

| Tank | Location | Liters | Kilograms | Notes |
|---|---|---|---|---|
| Main Tank No. 1 | Left wing box (integral) | 4,875 | 3,915 | See [[Components/Main-Tanks\|Main Tanks]] |
| Main Tank No. 2 | Right wing box (integral) | 4,875 | 3,915 | See [[Components/Main-Tanks\|Main Tanks]] |
| Center Tank | Wing root / fuselage | 16,273 | 13,066 | See [[Components/Center-Tank\|Center Tank]] |
| **TOTAL** | — | **26,025** | **20,896** | Fuel density 0.8029 kg/L |

> [!note] Why a Center Tank?
> Center tank is fuelled when fuel required for the flight exceeds ~7.8 tons (full main tanks) — driven by load distribution and wing loading, not simple capacity.

## 🔁 Fuel Feed Priority

| Phase | Fed From |
|---|---|
| Normal, center tank fuel available | **Center tank** → both engines (pressure fed) |
| Center tank quantity → near zero | **Respective main tank** → each engine |
| Main pump pressure low/unavailable | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Suction-Feed\|Suction feed]] from main tank |

> [!warning] Check Valves
> Check valves throughout the fuel system enforce correct flow direction and **prevent fuel transfer between tanks** outside of designed paths (crossfeed, scavenge, refuel/defuel).

## 🌡 Fuel Temperature

See [[Components/Fuel-Temperature-Indication|Fuel Temperature Indication]] for full limits and sensor placement rationale.

| Limit | Value |
|---|---|
| Maximum fuel temperature | 49 °C |
| Minimum fuel temperature | −43 °C, or 3 °C above fuel freeze point (whichever higher) |
| Jet A-1 freeze point (reference) | ≈ −47 °C |
| Sensor location | Main Tank No. 1 |

## 🔌 APU Fuel Feed

See [[Components/APU-Fuel-Feed|APU Fuel Feed]] for supply logic.

## 🧭 Components in This Section

| Page | Summary |
|---|---|
| [[Components/Main-Tanks\|Main Tanks]] | No.1 / No.2 wing-box tanks, wing rib bays, check valve |
| [[Components/Center-Tank\|Center Tank]] | Fuelling logic, location, capacity |
| [[Components/Surge-Tanks\|Surge Tanks]] | Overflow collection, vent scoop drainage |
| [[Components/Fuel-Temperature-Indication\|Fuel Temperature Indication]] | Limits, sensor placement, 737-200 legacy rationale |
| [[Components/APU-Fuel-Feed\|APU Fuel Feed]] | AC-pump vs suction supply to APU |

> [!info] Related
> Fuel pumps that move fuel out of these tanks are covered in [[../02-Fuel-Pumps-and-Suction-Feed/Overview|02 — Fuel Pumps & Suction Feed]].
