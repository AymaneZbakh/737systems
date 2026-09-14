---
tags: [electrical, standby-power, component, switch]
system: Electrical
parent: "[[05-DC-Standby-Power-System]]"
---

🔗 [[Fuel/Home]] | [[SPCU|← Previous]] | [[RCCB|Next →]]

# 🔧 Standby Power Switch

> [!abstract] Overview
> Three positions determine whether the AC/DC Standby Buses and Static Inverter are powered, and from what source.

## 🎛 Switch Positions

| Position | Effect |
|---|---|
| **OFF** | AC/DC standby buses and static inverter are **not powered** |
| **AUTO** | Automatic switching occurs from the normal sources of standby power (**XFR Bus 1, TR1, TR2, TR3**) to **battery power** when either Transfer Bus 1 or DC Bus 1 lose power |
| **BAT** | AC and DC standby buses are powered **by battery** |

> [!note] AUTO is the normal in-flight setting
> AUTO gives seamless AC-to-battery switchover without crew action — see [[RCCB]] for how the batteries get connected.

---
🔗 [[05-DC-Standby-Power-System]] · [[SPCU]] · [[Battery-Switch]] · [[RCCB]]
