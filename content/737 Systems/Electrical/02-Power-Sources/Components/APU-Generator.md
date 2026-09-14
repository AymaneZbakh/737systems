---
tags: [electrical, power-sources, component, apu]
system: Electrical
parent: "[[02-Power-Sources]]"
---

🔗 [[Fuel/Home]] | [[IDG|← Previous]] | [[Battery|Next →]]

# 🔧 APU Starter Generator

> [!abstract] Overview
> The APU generator both **starts the APU** and provides AC power once it is running, up to and beyond high altitudes with reduced capacity.

## 📋 Key Facts

| Parameter | Value |
|---|---|
| Function | APU starting, then AC power supply |
| Operating speed | 12,000 RPM |
| Output | 90 KVA up to 32,000 ft |
| Output above FL320 | Linearly decreases to 66 KVA at 41,000 ft |

## 🔧 APU Generator Control Unit (AGCU)

| Function |
|---|
| Controls APU generator output and the **Auxiliary Power Breaker (APB)** |
| Protects electrical system by tripping APB for overcurrent, over/underfrequency, etc. |
| Provides the same protection level as the IDG [[GCU|GCUs]] |

## 💡 Ready-to-Load / Available-for-Load Light

> [!note] Light illuminates when:
> - APU supplies the **Ready-To-Load** signal, **and**
> - Auxiliary Power Breaker is **open** (APU not yet providing power to any Transfer Bus)
>
> Ready-to-load signal appears at ≈**95%** of APU start speed.

## ⚙️ Auto Generator Online Feature

> [!note] Automatic reversion after takeoff
> If the APU is supplying both Transfer Buses and then fails or is inadvertently shut down **after takeoff**, the respective engine generators automatically connect to the Transfer Buses.

---
🔗 [[02-Power-Sources]] · See [[07-No-AC-Power-Reference]] for what remains powered if all AC is lost
