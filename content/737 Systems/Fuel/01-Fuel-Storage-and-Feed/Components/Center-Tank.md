---
tags: [fuel, component, tank, center-tank]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[Main-Tanks|← Previous]] | [[Surge-Tanks|Next →]]

# 🛢 Center Tank

> [!abstract] Overview
> The center tank lies between the wing roots within the fuselage area and extends into the wing structure. It is fuelled only when flight fuel requirements exceed the capacity of both main tanks.

## 📋 Quick Facts

| Parameter | Value |
|---|---|
| Location | Between wing roots, fuselage area, extends into wing |
| Capacity | 16,273 L / 13,066 kg |
| Fuelled when | Required fuel > 7.8 tons (full main tanks) |
| Reason for threshold | Load distribution & wing loading |
| Feed priority | **Used first** — center pumps output higher pressure than main pumps |
| Flammability reduction | [[../../06-Nitrogen-Generation-System/Overview\|Nitrogen Generation System (NGS)]] delivers NEA to this tank |
| Residual fuel recovery | [[../../02-Fuel-Pumps-and-Suction-Feed/Components/Center-Tank-Fuel-Scavenge-Jet-Pump\|Center Tank Fuel Scavenge Jet Pump]] → Main Tank 1 |

> [!warning] AC Transfer Bus Loss
> If AC transfer buses lose power, the **remaining fuel in the center tank cannot be retrieved** — center tank pumps are AC powered only.

## 🔗 Cross-References

- [[../../02-Fuel-Pumps-and-Suction-Feed/Components/Center-Tank-Fuel-Pumps|Center Tank Fuel Pumps]]
- [[../../06-Nitrogen-Generation-System/Overview|Nitrogen Generation System]]
- [[../../04-Fuel-Quantity-Indication/Components/Fuel-Alerts|FUEL CONFIG Alert]] (relates to center tank pump status)
