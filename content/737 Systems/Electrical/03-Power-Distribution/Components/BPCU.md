---
tags: [electrical, power-distribution, component, bpcu]
system: Electrical
parent: "[[03-Power-Distribution]]"
---

🔗 [[Fuel/Home]] | [[GCU|← Previous]] | [[AGCU|Next →]]

# 🔧 Bus Power Control Unit (BPCU)

> [!abstract] Overview
> The BPCU is the master controller of the AC power system — it enforces the no-paralleling rule, runs load shedding, and supervises ground power quality.

## 📋 Key Facts

| Function |
|---|
| Monitors and controls the **AC power system** |
| Ensures **no paralleling** of AC sources |
| Controls **load shed function** (main buses and galley buses) — see [[Auto-Load-Shedding]] |
| Monitors the **External Power Contactor (EPC)** |
| Controls [[GCU]], [[AGCU]], and the EPC relay |
| Controls the [[Bus-Tie-Breakers]] |

## 💡 GRD POWER AVAILABLE Light

> [!note] Illuminates when ground power is connected and power quality is within limits
> - Illuminates **even when the battery switch is OFF**
> - Always bright — **ignores** the master dim/bright switch
> - The BPCU disconnects ground power automatically if there is any failure or deviation in voltage, current, or frequency


---
🔗 [[03-Power-Distribution]] · [[Bus-Tie-Breakers]] · [[Ground-Power]] · [[Auto-Load-Shedding]]
