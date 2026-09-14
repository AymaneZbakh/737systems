---
tags: [fuel, component, ngs]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[../Overview]] | [[NGS-Indicator-Lights|Next →]]

# 🌬 NGS Operation

> [!abstract] Overview
> Fully automatic conversion of bleed air into nitrogen-enriched air, feeding the center tank throughout most of the flight envelope.

## 📋 Quick Facts

| Parameter | Value |
|---|---|
| Source air | Bleed air, left side |
| Output | Nitrogen-enriched air (NEA) |
| Destination | Center fuel tank |
| O₂ reduction in center tank | ≈ 12% |
| Auto-start | After take-off |
| Auto-stop | Taxi-in, after a specified time, or when bleed pressure unavailable |
| Float valve | Stops NEA flow when center tank is full |

## 🛑 Automatic Shutdown Conditions

- Aircraft on ground, not in test mode (air-ground sensor = ground)
- Either engine not running in flight
- Fire or smoke in cargo hold / main deck areas
- Left pack overheat
- Center tank refueling valve open

> [!note] MEL Dispatch
> Dispatch with NGS **inoperative** is acceptable under MEL — the fuel tank is primarily protected by removing ignition sources, not solely by inerting.

## 🔗 Cross-References

- [[../../01-Fuel-Storage-and-Feed/Components/Center-Tank|Center Tank]]
- [[NGS-Indicator-Lights|NGS Indicator Lights]]
