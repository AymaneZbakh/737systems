---
tags: [electrical, standby-power, component, battery-bus]
system: Electrical
parent: "[[05-DC-Standby-Power-System]]"
---

🔗 [[Fuel/Home]] | [[Battery-Switch|← Previous]] | [[Static-Inverter|Next →]]

# 🔧 Battery Buses (Hot & Switched Hot)

> [!abstract] Overview
> Two dedicated battery buses feed the aircraft's most safety-critical systems — one that is always alive, and one that follows the BAT switch.

## 📋 Bus Reference

| Bus | Powered When | Feeds |
|---|---|---|
| **Hot Battery Bus** | **Always** — regardless of BAT or STDBY PWR switch position | Fire Protection, Fuel Spar Valves, etc. |
| **Switched Hot Battery Bus** | `BAT` switch **ON** | Fire Protection, Left IRS, ADIRUs, etc. |

> [!warning] Hot Battery Bus is the last line of defense
> Because it is powered no matter what, the Hot Battery Bus is reserved for the most safety-critical loads — see [[Battery]].

---
🔗 [[05-DC-Standby-Power-System]] · [[Battery-Switch]] · [[Battery]] · [[RCCB]]
