---
tags: [electrical, power-distribution, 737]
system: Electrical
parent: "[[02-Power-Sources]]"
---

🔗 [[Fuel/Home]] | [[02-Power-Sources|← Previous]] | [[04-AC-Power-System|Next →]]

# 🖥 03 — Power Distribution

> [!abstract] Overview
> Electrical power is routed from its sources through feeder wires to two **Power Distribution Panels (PDPs)** in the E&E bay. Control units — [[GCU]], [[BPCU]], [[AGCU]] — supervise the whole distribution scheme, while [[Transformer-Rectifier|TRs]] convert AC to DC.

## 🔧 Components

| Component | Summary |
|---|---|
| [[GCU]] | Controls on-side GCB & BTB, monitors transfer bus health |
| [[BPCU]] | Master AC power control, no-paralleling enforcement, load shed |
| [[AGCU]] | Same protection role as GCU, but for the APU generator |
| [[Transformer-Rectifier]] | Converts 115V AC → 28V DC |
| [[PDP]] | Physical panels housing busses & breakers in the E&E bay |

## 📊 PDP Contents at a Glance

| PDP 1 | PDP 2 |
|---|---|
| Generator Control Breaker #1 | Generator Control Breaker #2 |
| Auxiliary Power Breaker | External Power Contactor |
| Bus Tie Breaker #1 | Bus Tie Breaker #2 |
| AC Transfer Bus #1 | AC Transfer Bus #2 |
| Ground Service Bus #1 | Ground Service Bus #2 |
| DC Bus #1 | DC Bus #2 |

> [!note] Location
> Most **system** circuit breakers are on the **P6** and **P18** panels behind the flight crew. The [[BPCU]], [[GCU]]s and [[AGCU]] all live in the **E&E bay** and control the distribution scheme centrally. See [[Circuit-Breakers]].

---
See also: [[Fuel/Summary/System Overview]] · [[Fuel/Quick-Reference/Key Numbers]]
