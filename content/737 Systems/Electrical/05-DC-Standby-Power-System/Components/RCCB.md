---
tags: [electrical, standby-power, component, rccb]
system: Electrical
parent: "[[05-DC-Standby-Power-System]]"
---

🔗 [[Fuel/Home]] | [[Standby-Power-Switch|← Previous]] | [[Battery-Switch|Next →]]

# 🔧 Remote Control Circuit Breaker (RCCB)

> [!abstract] Overview
> The RCCB is the relay that lets both batteries jointly feed the standby power system when needed.

## 📋 Key Facts

| Fact |
|---|
| Normally **open** |

## 🔀 Closing Conditions

> [!note] RCCB closes when ANY of the following is true
> - **TR3 fails** and the [[Standby-Power-Switch]] is in **AUTO**
> - **AC Transfer Bus 1** or **DC Bus 1** loses power
> - **Standby Power switch is in BAT**

> [!note] When closed
> Lets **both batteries** supply power to the standby system.

---
🔗 [[05-DC-Standby-Power-System]] · [[Standby-Power-Switch]] · [[Battery-Buses]]
