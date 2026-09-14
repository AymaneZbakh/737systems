---
tags: [electrical, load-shedding, component, protection]
system: Electrical
parent: "[[06-Load-Shedding-and-Protection]]"
---

🔗 [[Fuel/Home]] | [[06-Load-Shedding-and-Protection|← Previous]] | [[CAB-UTIL-Switch|Next →]]

# 🔧 Auto Load Shedding

> [!abstract] Overview
> Load shedding removes electrical loads to keep current within limits. The [[BPCU]] runs three distinct types of automatic load shed, each triggered differently.

## 📋 Key Facts

| Fact |
|---|
| Load shedding = removal of electrical loads to keep current within limits |
| Controlled by the **[[BPCU]]** |
| Reset attempt: cycle the **[[CAB-UTIL-Switch\|CAB/UTIL]]** switch |

## ⚙️ Three Types of Automatic Load Shed

| Type | Trigger | Effect |
|---|---|---|
| **Configuration Load Shed (APU)** | APU is the **only** source of AC power during flight | All galley buses automatically shed |
| **Overcurrent Load Shed** | GCU or AGCU detects overcurrent of a generator or external power | Galley and main buses lose power depending on the electrical system configuration |
| **Command Load Shed** | APU ECU senses high APU EGT (possible overload) | Galley buses shed first; main buses shed if the overload condition continues |

## 📊 Auto Load Shedding Table

| Condition | GALLEY | MAIN BUS | BTB | GCB | EPC/APB |
|---|---|---|---|---|---|
| Config Load Shed — APU | AIR (shed) | — | — | — | — |
| Command Load Shed — APU | GND/AIR | AIR | — | — | — |
| Command Load Shed — APU+GEN | Side powered by APU is shed | — | — | — | — |
| Over Current — 2 Generators | Galley on affected GEN is shed | — | If condition continues — affected GEN | If condition continues — affected GEN | — |
| Over Current — 1 Generator | C&D, if condition continues A&B | If condition continues | If condition continues | If condition continues | — |
| Over Current — APU/GND PWR | C&D, if condition continues A&B | If condition continues | If condition continues (No.2/No.1) | — | If condition continues |

---
🔗 [[06-Load-Shedding-and-Protection]] · [[BPCU]] · [[CAB-UTIL-Switch]]
