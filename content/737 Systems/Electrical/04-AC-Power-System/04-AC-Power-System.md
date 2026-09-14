---
tags: [electrical, ac-power, 737]
system: Electrical
parent: "[[03-Power-Distribution]]"
---

🔗 [[Fuel/Home]] | [[03-Power-Distribution|← Previous]] | [[05-DC-Standby-Power-System|Next →]]

# 🎮 04 — AC Power System

> [!abstract] Overview
> The AC Transfer Buses are the heart of the no-paralleling rule. [[Bus-Tie-Breakers|Bus Tie Breakers]] and the [[CBTR|Cross Bus Tie Relay]] link or isolate them depending on how the [[Bus-Transfer-Switch]] is set, and a family of warning lights tells the crew exactly what's connected to what.

## 🔧 Components

| Component | Summary |
|---|---|
| [[Bus-Transfer-Switch]] | AUTO / OFF override for automatic bus power transfer |
| [[Bus-Tie-Breakers]] | Link Transfer Bus 1 & 2, controlled by [[BPCU]] |
| [[CBTR]] | Cross Bus Tie Relay — parallels the 3 TRs |
| [[Transfer-Bus-Warning-Lights]] | SOURCE OFF / GEN OFF BUS / TRANSFER BUS OFF |
| [[Ground-Power]] | External AC source & flight deck indication |
| [[Ground-Service]] | Servicing power without powering the flight deck |

## 🗺 AC Distribution Flow

```text
IDG 1 ─ GCU 1 ─ GCB 1 ─┐                         ┌─ GCB 2 ─ GCU 2 ─ IDG 2
                        ├─> AC TRANSFER BUS 1 ─BTB1─BTB2─ AC TRANSFER BUS 2 <─┤
APU Gen ─ AGCU ─ APB ──┤        │                              │              ├── Ground Power ─ EPC
                        │  MAIN BUS 1 / GALLEY C&D    MAIN BUS 2 / GALLEY A&B │
                        │  GROUND SERVICE BUS 1        GROUND SERVICE BUS 2  │
                        └──────────────── AC STANDBY BUS (Static Inverter) ──┘
```

> [!warning] No paralleling — ever
> It is **not possible** to power one Transfer Bus from the APU and the other from Ground Power simultaneously — that would violate the no-paralleling rule.

---
See also: [[Fuel/Summary/System Overview]] · [[Fuel/Quick-Reference/Warning Lights]]
