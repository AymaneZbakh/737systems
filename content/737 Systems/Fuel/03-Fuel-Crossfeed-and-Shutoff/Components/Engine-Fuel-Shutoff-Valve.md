---
tags: [fuel, component, shutoff-valve, hpsov]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[Spar-Fuel-Shutoff-Valve|← Previous]] | [[APU-Fuel-Shutoff-Valve|Next →]]

# 🔒 Engine Fuel Shutoff Valve

> [!abstract] Overview
> Fuel-actuated, solenoid-controlled valve powered from the battery bus. Internally, a Fuel Metering Valve (EEC controlled) and a High-Pressure Shutoff Valve (fire switch / start lever controlled, bypassing the EEC) both live within this assembly.

## 📋 Quick Facts

| Parameter | Value |
|---|---|
| Type | Fuel-actuated, solenoid controlled |
| Power source | BAT BUS |
| Closes when | Engine fire switch pulled, or start lever placed to CUTOFF |

## ⚙️ Internal Elements

| Element | Controlled By |
|---|---|
| Fuel Metering Valve | EEC |
| High-Pressure Shutoff Valve (HPSOV) | Engine FIRE SWITCH and START LEVER directly — **bypasses the EEC** |

> [!warning] Why the HPSOV Bypasses the EEC
> The HPSOV must be able to stop fuel flow even if the EEC has failed — hence it is wired directly to the fire switch and start lever rather than through EEC logic.

## 🔗 Cross-References

- [[Spar-Fuel-Shutoff-Valve|Spar Fuel Shutoff Valve]]
- [[Fuel-Shutoff-Battery|Fuel Shutoff Battery]]
