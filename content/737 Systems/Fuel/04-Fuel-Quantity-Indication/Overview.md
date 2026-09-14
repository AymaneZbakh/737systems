---
tags: [fuel, quantity, fqis, overview]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../03-Fuel-Crossfeed-and-Shutoff/Overview|← Previous]] | [[../05-Fueling-Defueling-Ground-Transfer/Overview|Next →]]

# 🖥 04 — Fuel Quantity Indication

> [!abstract] Overview
> The Fuel Quantity Indicating System (FQIS) calculates usable fuel in each tank and drives flight-deck displays, the refuel panel, and three annunciator-class alerts (LOW / CONFIG / IMBAL).

## 🖥 FQIS Data Flow

```
Tank Units (32) ─┐
Densitometers (3)├──► FQPU (Fuel Quantity Processor Unit) ──► FMCS
Compensators (3) ─┘         │                                CDS
                             └──────────────────────────────► Refueling Panel
```

See [[Components/FQIS|FQIS]] for power sources and accuracy.

## 🚨 Fuel Alerts Summary

| Alert | Trigger | Clears At |
|---|---|---|
| **FUEL LOW** | Main tank qty < 907 kg (2000 lb) *(version A)* or < 453 kg (1000 lb) *(version B)* | Increases to 1134 kg (2500 lb) / 567 kg (1250 lb) respectively |
| **FUEL CONFIG** | Engine running **and** center tank qty > 726 kg (1600 lb) **and** both center pumps LOW PRESS or OFF (model dependent) | Center qty decreases below 363 kg (800 lb) |
| **FUEL IMBAL** | Main tanks differ by > 453 kg (1000 lb) | Difference reduces to 91 kg (200 lb) |

> [!warning] Version-Dependent Thresholds
> FUEL LOW and FUEL CONFIG trigger logic **varies by aircraft version/model** — always confirm which threshold set applies to the specific tail. See [[Components/Fuel-Alerts|Fuel Alerts]] for full detail.

## 🧭 Components in This Section

| Page | Summary |
|---|---|
| [[Components/FQIS\|FQIS]] | Sensors, processor, power, accuracy |
| [[Components/Fuel-Quantity-Indicators\|Fuel Quantity Indicators]] | Flight deck & refuel panel displays |
| [[Components/Fuel-Measuring-Sticks\|Fuel Measuring Sticks]] | Manual backup verification |
| [[Components/Fuel-Alerts\|Fuel Alerts]] | FUEL LOW / CONFIG / IMBAL full detail |

> [!info] Related
> Refuel panel displays are also covered from the fueling-operations angle in [[../05-Fueling-Defueling-Ground-Transfer/Overview|05 — Fueling, Defueling & Ground Transfer]].
