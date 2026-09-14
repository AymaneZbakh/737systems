---
tags: [electrical, power-sources, component, battery, dc]
system: Electrical
parent: "[[02-Power-Sources]]"
---

🔗 [[Fuel/Home]] | [[APU-Generator|← Previous]] | [[Battery-Charger|Next →]]

# 🔧 Battery (Main & Auxiliary)

> [!abstract] Overview
> Two 24V Ni-Cad batteries supply essential systems whenever AC power sources are unavailable, and jointly provide up to 60 minutes of emergency power.

## 📋 Key Facts

| Parameter | Value |
|---|---|
| Type | 24V Nickel-Cadmium |
| Location | E&E compartment |
| Voltage range | 22–30V |
| Capacity | 48 Ah each |
| Combined emergency endurance | 60 minutes (30 min if only one battery installed) |

> [!note] Variant difference
> Some aircraft variants have **only one main battery installed**.

## 🔗 Isolation & Parallel Operation

> [!note] Normally isolated
> AUX and MAIN batteries operate in **parallel only** when:
> - `BAT` switch **ON** and Transfer Bus #1 or DC Bus #1 have no power (aircraft on Standby Power), **or**
> - **TR3 fails**

## 🚀 APU Start

| Fact                            | Detail                                                                                                       |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Power source for APU start      | **Main battery only**                                                                                        |
| Preferred source when available | Transfer Bus #1                                                                                              |
| Battery charger behaviour       | Auto-disconnects during APU start (prevents overload)                                                        |
| Drain per 60s start attempt     | ≈6.7 Ah / 4.2 min main battery power (variable with attempt length, quality, temperature, rate of discharge) |

## 💡 BAT DISCHARGE Light

> [!warning] Trips Master Caution + ELEC
> Illuminates on excessive battery current output — **except** during a DC-power APU start:
>
> | Current | Duration |
> |---|---|
> | 5 A | 95 s |
> | 15 A | 25 s |
> | 100 A | 1.2 s |

---
🔗 [[02-Power-Sources]] · [[Battery-Switch]] · [[Battery-Buses]] · [[Battery-Charger]]
