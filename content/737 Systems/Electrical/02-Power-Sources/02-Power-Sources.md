---
tags: [electrical, power-sources, 737]
system: Electrical
parent: "[[01-Electrical-Basics]]"
---

🔗 [[Fuel/Home]] | [[01-Electrical-Basics|← Previous]] | [[03-Power-Distribution|Next →]]

# ⚙️ 02 — Power Sources

> [!abstract] Overview
> Four independent sources can supply AC power to the aircraft — two [[IDG|IDGs]], the [[APU-Generator|APU Generator]], and [[Ground-Power]] — plus a DC backbone built from [[Battery|batteries]] and [[Battery-Charger|battery chargers]]. None of them are ever allowed to parallel.

## 🔧 Components

| Component | Summary |
|---|---|
| [[IDG]] | Converts variable engine speed to constant 24,000 RPM for AC generation |
| [[APU-Generator]] | APU starter-generator, 90 KVA up to FL320 |
| [[Battery]] | Main + Aux 24V Ni-Cad, essential/emergency power |
| [[Battery-Charger]] | Keeps batteries charged, powers battery buses in TR mode |

## 📊 AC Source Comparison

| Source | Rated Output | Special Behaviour |
|---|---|---|
| IDG (×2) | 90 KVA | Constant-speed drive at 24,000 RPM |
| APU Generator | 90 KVA → 66 KVA (FL320–FL410, linear decrease) | Also provides APU starting |
| Ground Power | 90 KVA | 115/200V, 400Hz; quality-checked by [[BPCU]] |

> [!note] Auto Generator Online
> If the APU is powering both Transfer Buses and then fails or is inadvertently shut down **after takeoff**, the respective engine generators automatically connect to the Transfer Buses.

---
See also: [[Fuel/Summary/System Overview]] · [[Fuel/Quick-Reference/Key Numbers]] · [[03-Power-Distribution]]
