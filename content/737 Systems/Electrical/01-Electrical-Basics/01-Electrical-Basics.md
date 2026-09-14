---
tags: [electrical, basics, 737]
system: Electrical
---

🔗 [[Fuel/Home]] | [[Fuel/Home|← Home]] | [[02-Power-Sources|Next →]]

# ✈ 01 — Electrical Basics

> [!abstract] Overview
> The 737 electrical system runs on two parallel networks — **AC** (115V, 3-phase, 400Hz) and **DC** (28V) — governed by two unbreakable design principles that shape every switch, light, and relay in the system.

## ⚙️ The Two Governing Principles

| #   | Principle                                       | Practical Effect                                                                                           |
| --- | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| 1   | **No paralleling of AC sources**                | Only one AC source may ever power a given Transfer Bus at a time                                           |
| 2   | **New source auto-disconnects existing source** | Connecting a new power source to a Transfer Bus automatically disconnects whatever was already powering it |

> [!warning] Why this matters
> Almost every abnormal light in this vault (`SOURCE OFF`, `TRANSFER BUS OFF`, `GEN OFF BUS`) exists to police these two rules. See [[Transfer-Bus-Warning-Lights]].

## 🔌 AC Power Sources

| Source            | Output                                                 | Notes                      |
| ----------------- | ------------------------------------------------------ | -------------------------- |
| [[IDG]] ×2        | 90 KVA each                                            | One per engine             |
| [[APU-Generator]] | 90 KVA up to FL320, linear decrease to 66 KVA at FL410 |                            |
| [[Ground-Power]]  | 90 KVA                                                 | 115/200V, 400Hz receptacle |

## 🔋 DC Power Sources

| Source | Notes |
|---|---|
| Main & Auxiliary [[Battery]] | 24V Ni-Cad, 48 Ah each |
| 3× [[Transformer-Rectifier]] (TR) | Converts 115V AC → 28V DC |
| Main & Auxiliary [[Battery-Charger]] | Converts 115V AC, charges the batteries |

## 🔋 Battery Fundamentals

| Parameter                | Value                                          |
| ------------------------ | ---------------------------------------------- |
| Battery type             | 24V Nickel-Cadmium                             |
| Location                 | E&E compartment                                |
| Voltage range            | 22–30V                                         |
| Capacity                 | 48 Ah each                                     |
| Combined emergency power | 60 min (30 min if single-battery installation) |

> [!note] Some aircraft variants
> Some variants have **only one main battery installed** — no Auxiliary Battery.

### Battery Isolation Rule

> [!note] Batteries are normally isolated
> AUX and MAIN Battery operate in **parallel only** when:
> - `BAT` switch **ON** *and* Transfer Bus #1 or DC Bus #1 have **no power** (on Standby Power), **or**
> - **TR3 fails**

### APU Start on Battery

| Fact | Detail |
|---|---|
| APU start power source | **Main battery only** (Transfer Bus #1 normally used when available) |
| Battery charger during APU start | Automatically disconnects — prevents overload |
| Drain per 60s start attempt | ≈6.7 Ah / 4.2 min of main battery power (variable) |

> [!warning] BAT DISCHARGE Light
> Master Caution + `ELEC` light illuminate — **except** during a DC-power APU start. Trips on excessive battery current:
>
> | Current | Duration |
> |---|---|
> | 5 A | 95 s |
> | 15 A | 25 s |
> | 100 A | 1.2 s |

---
See also: [[Fuel/Summary/System Overview]] · [[Fuel/Quick-Reference/Key Numbers]]
