---
tags: [fuel, quick-reference, numbers]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../Summary/System Overview|← Previous]] | [[Warning Lights|Next →]]

# 🔢 Key Numbers — Grouped by Subsystem

> [!abstract] Overview
> Every numeric limit, threshold, and capacity value in this vault, grouped by subsystem for fast lookup.

## 🛢 Capacities

| Item | Liters | Kilograms |
|---|---|---|
| Main Tank No. 1 | 4,875 | 3,915 |
| Main Tank No. 2 | 4,875 | 3,915 |
| Center Tank | 16,273 | 13,066 |
| **Total** | **26,025** | **20,896** |
| Surge tank (each) | — | 107 kg / 235 lb |
| Fuel density (reference) | — | 0.8029 kg/L |

See [[../01-Fuel-Storage-and-Feed/Overview|Fuel Storage & Feed]].

## ⚙️ Pumps

| Item | Value |
|---|---|
| Main pump output pressure | 10 psi |
| Center pump output pressure | 23 psi |
| Both pump types — flow rate | 9,071 kg/h (20,000 lb/h) |
| Main pump LOW PRESSURE threshold | < 4 psi |
| Center pump LOW PRESSURE threshold | < 22 psi |
| Center pump Master Caution delay | 10 seconds |
| Center pump auto-shutoff delay (certain models) | 15 seconds |
| Center tank fuel scavenge rate | 100–200 kg/h (220–440 lb/h) |
| Scavenge activation — Main Tank 1 qty | ≈ 1,990 kg / 4,300 lb |
| Suction feed flameout altitude (low end) | 13,000 ft |

See [[../02-Fuel-Pumps-and-Suction-Feed/Overview|Fuel Pumps & Suction Feed]].

## 🎮 Crossfeed & Shutoff

| Item | Value |
|---|---|
| Crossfeed valve type | Butterfly, DC motor, BAT BUS |
| Spar shutoff valve power | HOT BAT BUS + Fuel Shutoff Battery |
| Engine shutoff valve power | BAT BUS |
| APU shutoff valve power | HOT BAT BUS + Fuel Shutoff Battery |

See [[../03-Fuel-Crossfeed-and-Shutoff/Overview|Fuel Crossfeed & Shutoff]].

## 🖥 Quantity Indication & Alerts

| Item | Value |
|---|---|
| FQIS tank units | 32 |
| FQIS densitometers | 3 |
| FQIS compensators | 3 |
| FQIS max error — ground | 2.0% |
| FQIS max error — in flight | 2.5% |
| Fuel measuring sticks — main tank | 6 each |
| Fuel measuring sticks — center tank | 4 |
| FUEL LOW threshold (version A) | < 907 kg (2000 lb) → clears at 1134 kg (2500 lb) |
| FUEL LOW threshold (version B) | < 453 kg (1000 lb) → clears at 567 kg (1250 lb) |
| FUEL CONFIG center tank threshold | > 726 kg (1600 lb) → clears < 363 kg (800 lb) |
| FUEL IMBAL threshold | > 453 kg (1000 lb) → clears at 91 kg (200 lb) |

See [[../04-Fuel-Quantity-Indication/Overview|Fuel Quantity Indication]].

## 🌡 Temperature

| Item | Value |
|---|---|
| Maximum fuel temperature | 49 °C |
| Minimum fuel temperature | −43 °C, or 3 °C above freeze point (higher wins) |
| Jet A-1 freeze point (reference) | ≈ −47 °C |

See [[../01-Fuel-Storage-and-Feed/Components/Fuel-Temperature-Indication|Fuel Temperature Indication]].

## 🌬 NGS

| Item | Value |
|---|---|
| O₂ reduction in center tank | ≈ 12% |
| Auto-start | After take-off |
| Auto-stop | Taxi-in / timed / bleed pressure lost |

See [[../06-Nitrogen-Generation-System/Overview|Nitrogen Generation System]].
