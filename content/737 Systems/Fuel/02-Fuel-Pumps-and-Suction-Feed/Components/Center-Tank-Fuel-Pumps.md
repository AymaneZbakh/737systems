---
tags: [fuel, component, pump, center-tank]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[Main-Tank-Fuel-Pumps|← Previous]] | [[Suction-Feed|Next →]]

# ⚙️ Center Tank Fuel Pumps

> [!abstract] Overview
> Two AC-powered pumps producing higher pressure than main tank pumps, ensuring center tank fuel is consumed first. Certain models include an auto-shutoff feature that protects the pump when it runs dry.

## 📋 Quick Facts

| Parameter | Value |
|---|---|
| Pumps | 2 |
| Output pressure | 23 psi (higher than main pumps' 10 psi) |
| Flow rate | 9,071 kg/h (20,000 lb/h) |
| Power source | Transfer buses (AC) |
| Effect of AC transfer bus loss | Remaining center tank fuel **cannot be retrieved** |

## 🚨 LOW PRESSURE Light

> [!warning] Centre Fuel Pump LOW PRESSURE
> - Illuminates when output pressure is **< 22 psi** with the Center Fuel Pump switch **ON**
> - **10-second delay** before Master Caution illuminates
> - **(Certain models)** Auto-shutoff activates **15 seconds** after LOW PRESSURE is first detected
> - Restart after auto-shutoff: cycle the center pump switch **OFF then ON** — if LOW PRESSURE is still present, the pump shuts off again after another 15 seconds

> [!note] Flickering in Cruise
> One pump may indicate low pressure sooner than the other due to aircraft attitude and/or slight pump-inlet variation. Low pressure indication may occur **after center tank quantity reads zero**. Flickering can continue for up to **5 minutes** before Master Caution/FUEL annunciator illuminate for that pump.

> [!note] Switch Reset Logic
> Setting a center tank fuel pump switch to OFF **resets the auto-shutoff logic** for that pump. Setting it back ON re-activates the pump until switched OFF again, or until auto-shutoff logic deactivates it.

## 🔗 Cross-References

- [[../../01-Fuel-Storage-and-Feed/Components/Center-Tank|Center Tank]]
- [[../../04-Fuel-Quantity-Indication/Components/Fuel-Alerts|FUEL CONFIG Alert]] (relates to both center pumps LOW PRESS / OFF)
