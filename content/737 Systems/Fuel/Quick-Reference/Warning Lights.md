---
tags: [fuel, quick-reference, warning-lights]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[Key Numbers|← Previous]] | [[Variant Comparison|Next →]]

# 🚨 Warning & Advisory Lights

> [!abstract] Overview
> Every fuel-system light in this vault, its color, trigger condition, and clearing condition, plus notes on which are new, renamed, or model/variant dependent.

## 📋 Full Light Table

| Light | Color | Illuminates When | Clears / Notes |
|---|---|---|---|
| Main Fuel Pump LOW PRESSURE | Amber | Output < 4 psi, or switch OFF | Master Caution on RECALL (1 light) or direct (2 lights) |
| Centre Fuel Pump LOW PRESSURE | Amber | Output < 22 psi, switch ON | 10s delay to Master Caution; auto-shutoff 15s (certain models) |
| FILTER BYPASS | Amber | Contaminated fuel filter — impending bypass | Engine may run erratically/flame out |
| FUEL LOW | Amber | < 907 kg or < 453 kg in main tank (version dependent) | Clears at 1134 kg / 567 kg respectively |
| FUEL CONFIG | Amber | Engine running + center tank > 726 kg + both center pumps OFF/LOW PRESS | Clears < 363 kg |
| FUEL IMBAL | Amber | Main tanks differ > 453 kg | Clears at 91 kg difference |
| CROSSFEED VALVE OPEN | Blue | Bright = in transit / disagreement; Dim = valve open | Extinguished = valve closed |
| Fueling VALVE POSITION | Blue | Switch OPEN and tank not full | Extinguished when full or switch CLOSED |
| NGS OPERATIONAL | Green | NGS fully operational | Wheel-well indicator only, no cockpit light |
| NGS DEGRADED | Blue | NGS operational but degraded/temporarily serviceable | Wheel-well indicator only |
| NGS INOPERATIVE | Amber | NGS inoperative | Also indicated by **no lights** illuminated |

> [!warning] Safety-Critical Lights
> - **Centre/Main Fuel Pump LOW PRESSURE** — can precede suction feed and flameout risk
> - **FILTER BYPASS** — can precede engine flameout
> - **FUEL IMBAL** combined with an unannunciated crossfeed leak risk — see [[../03-Fuel-Crossfeed-and-Shutoff/Components/Crossfeed-Valve|Crossfeed Valve]]

> [!note] No Cockpit NGS Indication
> NGS status is **new-generation, wheel-well only** — there has never been a flight deck light for it. Don't expect an EICAS/annunciator entry.

## 🔗 Related

- [[../04-Fuel-Quantity-Indication/Components/Fuel-Alerts|Fuel Alerts (full detail)]]
- [[../02-Fuel-Pumps-and-Suction-Feed/Overview|Fuel Pumps & Suction Feed]]
- [[../06-Nitrogen-Generation-System/Components/NGS-Indicator-Lights|NGS Indicator Lights]]
