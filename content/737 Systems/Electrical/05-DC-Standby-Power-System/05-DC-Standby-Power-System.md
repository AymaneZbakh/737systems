---
tags: [electrical, dc-power, standby-power, 737]
system: Electrical
parent: "[[04-AC-Power-System]]"
---

🔗 [[Fuel/Home]] | [[04-AC-Power-System|← Previous]] | [[06-Load-Shedding-and-Protection|Next →]]

# 🛩 05 — DC & Standby Power System

> [!abstract] Overview
> The Standby Power System keeps essential systems alive so the flight can be **safely completed even if all AC power sources fail**. The [[SPCU]] governs the switchover between AC-derived standby power and battery power, backstopped by a chain of battery buses.

## 🔧 Components

| Component | Summary |
|---|---|
| [[SPCU]] | Standby Power Control Unit — governs standby relays |
| [[Standby-Power-Switch]] | OFF / AUTO / BAT |
| [[RCCB]] | Remote Control Circuit Breaker — parallels the batteries onto standby |
| [[Battery-Switch]] | BAT ON/OFF and its cascading effects |
| [[Battery-Buses]] | Hot Battery Bus & Switched Hot Battery Bus |
| [[Static-Inverter]] | DC → AC conversion for the AC Standby Bus |

## 🗺 Standby Power Buses

| Bus | Description |
|---|---|
| AC Standby Bus | Fed via [[Static-Inverter]] from DC, or from AC sources |
| DC Standby Bus | DC backbone of the standby system |
| Battery Bus | Direct battery-fed bus |
| Switched Hot Battery Bus | Powered only when `BAT` switch is ON |
| Hot Battery Bus | **Always** powered, regardless of switch positions |

```text
NORMAL:     XFR BUS 1 / TR1,2,3 ──> STANDBY POWER SYSTEM
LOSS OF XFR BUS 1 or DC BUS 1:  MAIN + AUX BATTERY ──(via RCCB)──> STANDBY POWER SYSTEM
```

> [!warning] SPCU enforces single-source rule
> The [[SPCU]] ensures that **only one source** (batteries OR AC power sources) powers the Standby Power System at any given time.

---
See also: [[Fuel/Summary/System Overview]] · [[Comparison]]
