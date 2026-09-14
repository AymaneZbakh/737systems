---
tags: [electrical, quick-reference, warning-lights]
---

🔗 [[Fuel/Home]] | [[Electrical/Quick-Reference/Key Numbers|← Previous]] | [[Comparison|Next →]]

# 💡 Warning Lights

> [!abstract] Overview
> Every annunciator light referenced in the vault, with its trigger condition and the page where it's discussed in detail.

| Light | System | Condition | Details |
|---|---|---|---|
| **DRIVE** | [[IDG]] | IDG low oil pressure — underfrequency, low oil pressure, or auto-disconnect at 182°C/363°F oil temp | [[IDG]] |
| **GRD POWER AVAILABLE** | [[Ground-Power]] / [[BPCU]] | Ground power connected & within quality limits; only light left after full power-down | [[Ground-Power]] |
| **GEN OFF BUS** | [[Transfer-Bus-Warning-Lights]] | GCB open — not powering its Transfer Bus (regardless of IDG running) | [[Transfer-Bus-Warning-Lights]] |
| **SOURCE OFF** | [[Transfer-Bus-Warning-Lights]] | No source manually selected, or selected source disconnected — can indicate generator failure/engine shutdown | [[Transfer-Bus-Warning-Lights]] |
| **TRANSFER BUS OFF** | [[Transfer-Bus-Warning-Lights]] | Related AC Transfer Bus has no power | [[Transfer-Bus-Warning-Lights]] |
| **TR UNIT** (ground) | [[Transformer-Rectifier]] | Any TR has failed | [[Transformer-Rectifier]] |
| **TR UNIT** (in flight) | [[Transformer-Rectifier]] | TR1 failed, or TR2 **and** TR3 failed | [[Transformer-Rectifier]] |
| **STANDBY PWR OFF** | [[SPCU]] | Battery/AC Standby/DC Standby bus unpowered or voltage low >2s | [[SPCU]] |
| **ELEC** | [[SPCU]] | Ground only — fault in DC or Standby Power system | [[SPCU]] |
| **BAT DISCHARGE** | [[Battery]] | Excessive battery current (5A/95s, 15A/25s, 100A/1.2s) — except during DC-power APU start | [[Battery]] |
| **AVAILABLE FOR LOAD / Ready-to-Load** | [[APU-Generator]] | APU Ready-to-Load signal + APB open; comes on ~95% of start speed | [[APU-Generator]] |
| **PACK light** | [[07-No-AC-Power-Reference]] | Air conditioning pack valve status (available with no AC power) | [[07-No-AC-Power-Reference]] |
| **FUEL VALVE CLOSED** | [[07-No-AC-Power-Reference]] | Spar/engine shutoff valve closed (available with no AC power) | [[07-No-AC-Power-Reference]] |
| **ANTISKID INOP** | [[07-No-AC-Power-Reference]] | Inboard anti-skid system fault (available with no AC power) | [[07-No-AC-Power-Reference]] |

> [!warning] Cross-check engine instruments
> `SOURCE OFF` in particular can be the first sign of a **generator failure or engine shutdown** — always verify against engine instruments.

---
See also: [[Fuel/Home]] · [[Electrical/Quick-Reference/Key Numbers]] · [[Comparison]]
