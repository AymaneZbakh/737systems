---
tags: [electrical, power-sources, component, battery-charger]
system: Electrical
parent: "[[02-Power-Sources]]"
---

🔗 [[Fuel/Home]] | [[Battery|← Previous]] | [[03-Power-Distribution|Next →]]

# 🔧 Battery Charger

> [!abstract] Overview
> Two battery chargers — one per battery — convert 115V AC to keep the batteries charged and to power the battery buses when operating in Transformer Rectifier mode.

## 📋 Key Facts

| Parameter | Value |
|---|---|
| Number of chargers | 2 (one per battery), located in E&E bay |
| AUX charger power source | GND Service Bus #1 |
| MAIN charger power source | GND Service Bus #2 |
| Input | 115V AC |
| Functions | 1) Keep battery fully charged · 2) Supply power to the battery busses |

## ⚙️ Two Operating Modes

| Mode                           | Trigger                             | Behaviour                                                                               |
| ------------------------------ | ----------------------------------- | --------------------------------------------------------------------------------------- |
| **Battery Charge Mode**        | Battery voltage drops **below 23V** | Charges the battery. Inhibited when fueling panel is open or APU is being started       |
| **Transformer Rectifier Mode** | Default / most of the time          | Powers Hot Battery Bus + Switched Hot Battery Bus at constant **27.5V**, up to **65 A** |

> [!note] Most of the time
> The charger spends most of its operating life in **Transformer Rectifier Mode**, directly backing up the [[Battery-Buses|Hot Battery Bus and Switched Hot Battery Bus]].

---
🔗 [[02-Power-Sources]] · [[Battery]] · [[Battery-Buses]]
