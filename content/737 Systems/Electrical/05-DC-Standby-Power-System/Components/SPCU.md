---
tags: [electrical, standby-power, component, spcu]
system: Electrical
parent: "[[05-DC-Standby-Power-System]]"
---

🔗 [[Fuel/Home]] | [[05-DC-Standby-Power-System|← Previous]] | [[Standby-Power-Switch|Next →]]

# 🔧 Standby Power Control Unit (SPCU)

> [!abstract] Overview
> Located in the Flight Deck, the SPCU is the brain of the standby power system — it ensures essential systems keep running through any single AC failure, without ever letting two sources power the standby buses at once.

## 📋 Key Facts

| Function |
|---|
| Powers essential systems so flight can be **safely completed** even with all AC power sources failed |
| Controls the standby power relays |
| Ensures only **one source** (Batteries **or** AC power sources) powers the Standby Power System at a time |

## 🗺 Buses Under SPCU Control

| Bus |
|---|
| AC Standby Bus |
| DC Standby Bus |
| Battery Bus |
| Switched Hot Battery Bus |
| Hot Battery Bus |

## 🔀 Switchover Logic

> [!note] Automatic source selection
> When available, **AC power sources** supply the standby power system. When **Transfer Bus 1** or **DC Bus 1** lose power, **main and auxiliary battery** take over via the [[RCCB]].

## 💡 Lights

| Light | Condition |
|---|---|
| **STANDBY PWR OFF** | One or more of Battery Bus / AC Standby Bus / DC Standby Bus is unpowered, or its voltage drops below **100V AC / 17.5V DC** for more than **2 seconds** |
| **ELEC** | Illuminates **on the ground only** — indicates a fault in the DC system or Standby Power system |

---
🔗 [[05-DC-Standby-Power-System]] · [[Standby-Power-Switch]] · [[RCCB]]
