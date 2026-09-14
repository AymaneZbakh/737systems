---
tags: [fuel, component, fqis]
system: Fuel
parent: "[[../Overview]]"
---

🔗 [[Home]] | [[../Overview]] | [[Fuel-Quantity-Indicators|Next →]]

# 🖥 Fuel Quantity Indicating System (FQIS)

> [!abstract] Overview
> Calculates the usable fuel quantity in each tank using tank units, densitometers, and compensators, and distributes the result to the FMCS, CDS, and refueling panel via the Fuel Quantity Processor Unit (FQPU).

## 📋 Quick Facts

| Parameter | Value |
|---|---|
| Tank units | 32 |
| Densitometers | 3 |
| Compensators | 3 |
| Processes through | Fuel Quantity Processor Unit (FQPU) |
| Data delivered to | FMCS, CDS, Refueling Panel |
| Power sources | DC Bus 1, Battery Bus, Hot Battery Bus (any) |
| Max error — ground | 2.0% |
| Max error — in flight | 2.5% |

> [!note] Overfill Indication
> Fuel quantity **blinks on the refueling panel** if the corresponding tank has been overfilled.

## 🔗 Cross-References

- [[Fuel-Quantity-Indicators|Fuel Quantity Indicators]]
- [[../../05-Fueling-Defueling-Ground-Transfer/Components/Refueling-Panel|Refueling Panel]]
