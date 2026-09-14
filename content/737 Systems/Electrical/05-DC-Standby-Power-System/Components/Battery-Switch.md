---
tags: [electrical, standby-power, component, battery-switch]
system: Electrical
parent: "[[05-DC-Standby-Power-System]]"
---

🔗 [[Fuel/Home]] | [[RCCB|← Previous]] | [[Battery-Buses|Next →]]

# 🔧 Battery Switch

> [!abstract] Overview
> The BAT switch's effect on the buses depends heavily on what else is going on — normal AC power, battery-only power, or Standby Power in BAT.

## 🎛 BAT OFF — Scenario Matrix

| Scenario | Buses that lose power |
|---|---|
| **BAT OFF** + Normal AC power, Standby power in AUTO | Battery Bus, Switched Hot Battery Bus |
| **BAT OFF** + Battery is the only source of power | Battery Bus, Switched Hot Battery Bus, AC Standby Bus, DC Standby Bus, Static Inverter |
| **BAT OFF** + Standby power in BAT | **Only** Switched Hot Battery Bus |

> [!warning] Hot Battery Bus is never affected
> The **Hot Battery Bus** stays powered in every scenario above — see [[Battery-Buses]].

---
🔗 [[05-DC-Standby-Power-System]] · [[RCCB]] · [[Battery-Buses]] · [[Standby-Power-Switch]]
