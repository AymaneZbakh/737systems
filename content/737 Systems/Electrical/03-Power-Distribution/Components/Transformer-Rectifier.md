---
tags: [electrical, power-distribution, component, tr, dc]
system: Electrical
parent: "[[03-Power-Distribution]]"
---

🔗 [[Fuel/Home]] | [[AGCU|← Previous]] | [[PDP|Next →]]

# 🔧 Transformer Rectifier (TR)

> [!abstract] Overview
> Three Transformer Rectifiers convert 115V AC into 28V DC, normally sharing the load in parallel via the Cross Bus Tie.

## 📋 Key Facts

| Parameter | Value |
|---|---|
| Number of TRs | 3 |
| Conversion | 115V AC → 28V DC |
| Continuous load rating (each) | 75 A |
| Normal load — TR1 & TR2 | 16–20 A |
| Normal load — TR3 | 9–14 A |

## 🔗 Parallel Operation

> [!note] TRs are connected in parallel
> They share the load through the [[CBTR|Cross Bus Tie Relay (CBTR)]]. When the cross bus tie is **open**:
>
> | TR | Powers |
> |---|---|
> | TR 1 | DC Bus 1 |
> | TR 2 | DC Bus 2 |
> | TR 3 | Battery Bus and DC Bus 2 |

## 💡 TR Unit Light

| Condition | Trigger |
|---|---|
| **On ground** | Any TR has failed |
| **In flight** | TR1 failed, **or** TR2 and TR3 both failed |

---
🔗 [[03-Power-Distribution]] · [[CBTR]] · [[Battery-Buses]]
