---
tags: [fuel, summary]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../06-Nitrogen-Generation-System/Overview|← Previous]] | [[../Quick-Reference/Key Numbers|Next →]]

# 📊 Summary — Fuel System Overview

> [!abstract] Overview
> One consolidated table of every subsystem, its key facts, power source, and governing document section — for fast lookup without navigating the full vault.

## 📋 Consolidated System Table

| Subsystem | Key Fact | Power Source | Primary Page |
|---|---|---|---|
| Main Tanks (No.1/No.2) | 3,915 kg each, rib-8 check valve (inboard flow only) | — | [[../01-Fuel-Storage-and-Feed/Components/Main-Tanks\|Main Tanks]] |
| Center Tank | 13,066 kg, fuelled when required fuel > 7.8 t | — | [[../01-Fuel-Storage-and-Feed/Components/Center-Tank\|Center Tank]] |
| Surge Tanks | 107 kg each, overflow collection | — | [[../01-Fuel-Storage-and-Feed/Components/Surge-Tanks\|Surge Tanks]] |
| Fuel Temperature | 49 °C max / −43 °C or 3 °C above freeze pt min | AC | [[../01-Fuel-Storage-and-Feed/Components/Fuel-Temperature-Indication\|Fuel Temp]] |
| APU Fuel Feed | Left manifold (pumps on) / suction Tank 1 (pumps off) | — | [[../01-Fuel-Storage-and-Feed/Components/APU-Fuel-Feed\|APU Fuel Feed]] |
| Main Tank Pumps | 10 psi, 9,071 kg/h, LOW PRESS < 4 psi | AC transfer bus | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Main-Tank-Fuel-Pumps\|Main Pumps]] |
| Center Tank Pumps | 23 psi, LOW PRESS < 22 psi, 15s auto-shutoff (some models) | AC transfer bus | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Center-Tank-Fuel-Pumps\|Center Pumps]] |
| Suction Feed | Bypasses pumps; flameout risk as low as 13,000 ft | — | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Suction-Feed\|Suction Feed]] |
| Scavenge Jet Pump | 100–200 kg/h to Main Tank 1, starts at ~half full | — (jet pump, no motor) | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Center-Tank-Fuel-Scavenge-Jet-Pump\|Scavenge Pump]] |
| Filter Bypass | Contaminated filter warning | — | [[../02-Fuel-Pumps-and-Suction-Feed/Components/Fuel-Filter-Bypass\|Filter Bypass]] |
| Crossfeed Valve | Butterfly, connects L/R manifolds | BAT BUS (DC motor) | [[../03-Fuel-Crossfeed-and-Shutoff/Components/Crossfeed-Valve\|Crossfeed Valve]] |
| Spar Shutoff Valve | Closes on fire switch / CUTOFF | HOT BAT BUS + Shutoff Battery | [[../03-Fuel-Crossfeed-and-Shutoff/Components/Spar-Fuel-Shutoff-Valve\|Spar Shutoff]] |
| Engine Shutoff Valve | HPSOV bypasses EEC | BAT BUS | [[../03-Fuel-Crossfeed-and-Shutoff/Components/Engine-Fuel-Shutoff-Valve\|Engine Shutoff]] |
| APU Shutoff Valve | Rear spar, wheel-well access | HOT BAT BUS + Shutoff Battery | [[../03-Fuel-Crossfeed-and-Shutoff/Components/APU-Fuel-Shutoff-Valve\|APU Shutoff]] |
| FQIS | 32 tank units, 3 densitometers, 3 compensators, ≤2.5% error | DC Bus 1 / Bat Bus / Hot Bat Bus | [[../04-Fuel-Quantity-Indication/Components/FQIS\|FQIS]] |
| Fuel Alerts | LOW / CONFIG / IMBAL — version-dependent thresholds | — | [[../04-Fuel-Quantity-Indication/Components/Fuel-Alerts\|Fuel Alerts]] |
| Refueling Panel | Single point, R wing leading edge | Ground/AC/Battery | [[../05-Fueling-Defueling-Ground-Transfer/Components/Refueling-Panel\|Refuel Panel]] |
| Manual Defueling Valve | Pressure (any tank) / Suction (Tank 2 only) | — | [[../05-Fueling-Defueling-Ground-Transfer/Components/Manual-Defueling-Valve\|Defuel Valve]] |
| NGS | Bleed air → NEA → center tank, no cockpit indication | Bleed air (pneumatic) | [[../06-Nitrogen-Generation-System/Overview\|NGS]] |

## 🆚 Feed Priority at a Glance

| Order | Source | Trigger |
|---|---|---|
| 1st | Center tank | Always, until near-empty |
| 2nd | Main tanks (pressure) | Center tank near zero |
| 3rd | Main tanks (suction) | Main pump pressure low |

> [!tip] Fast Lookup
> For raw numbers only, jump straight to [[../Quick-Reference/Key Numbers|Key Numbers]].
