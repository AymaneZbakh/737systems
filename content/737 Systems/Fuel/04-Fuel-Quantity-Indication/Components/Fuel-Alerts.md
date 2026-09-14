---
tags: [fuel, component, alert, warning]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[Fuel-Measuring-Sticks|← Previous]] | [[../../05-Fueling-Defueling-Ground-Transfer/Overview|Next →]]

# 🚨 Fuel Alerts

> [!abstract] Overview
> Three annunciator-class fuel alerts — FUEL LOW, FUEL CONFIG, and FUEL IMBAL — each with version-dependent trigger and clear thresholds.

## 🟠 FUEL LOW

| Version | Illuminates Below | Clears At |
|---|---|---|
| Version A | 907 kg (2000 lb) in main tank | 1134 kg (2500 lb) |
| Version B | 453 kg (1000 lb) in main tank | 567 kg (1250 lb) |

> [!note] Display Behaviour by Variant
> - **CN-RGE–RGV, CN-RNP–ROZ:** the fuel quantity **arc and digits** on the affected tank turn amber.
> - **CN-RGW:** only the fuel quantity **digits** turn amber (digital-only display, no arc).

## 🟠 FUEL CONFIG

> [!warning] Illuminates When ALL of the following are true
> - Either engine is running
> - Center fuel tank quantity is **greater than 726 kg (1600 lb)**
> - **(Certain models)** both center tank pump switches are **OFF**, **or** **(certain models)** both center tank pumps show **LOW PRESS**

| Behaviour | Detail |
|---|---|
| Clears at | Center tank quantity decreases below 363 kg (800 lb) |
| Display effect (CN-RGE–RGV, RNP–ROZ) | Center tank quantity arc and digits turn amber |

## 🟠 FUEL IMBAL

| Parameter | Value |
|---|---|
| Illuminates when | Main tanks differ by **> 453 kg (1000 lb)** |
| Extinguishes when | Difference reduces to **91 kg (200 lb)** |

> [!info] Related
> See [[../../03-Fuel-Crossfeed-and-Shutoff/Components/Crossfeed-Valve|Crossfeed Valve]] for how imbalance is corrected in flight.

## 🔗 Cross-References

- [[FQIS|FQIS]]
- [[../../03-Fuel-Crossfeed-and-Shutoff/Components/Crossfeed-Valve|Crossfeed Valve]]
- [[../../02-Fuel-Pumps-and-Suction-Feed/Components/Center-Tank-Fuel-Pumps|Center Tank Fuel Pumps]]
