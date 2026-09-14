---
tags: [electrical, summary, system-overview]
---

🔗 [[Fuel/Home]] | [[07-No-AC-Power-Reference|← Previous]] | [[Fuel/Quick-Reference/Key Numbers|Next →]]

# 📖 System Overview

> [!abstract] Overview
> One consolidated table per functional area — every major fact from the vault, cross-linked, in one scrolling reference.

## ⚙️ AC Power Sources

| Source | Output | Key Control | Notes |
|---|---|---|---|
| [[IDG]] ×2 | 90 KVA | [[GCU]] | Constant 24,000 RPM |
| [[APU-Generator]] | 90 KVA → 66 KVA (FL320–FL410) | [[AGCU]] | Also starts APU, 12,000 RPM |
| [[Ground-Power]] | 90 KVA | [[BPCU]] | 115/200V, 400Hz |

## 🔌 DC Power Sources

| Source | Output | Notes |
|---|---|---|
| [[Transformer-Rectifier]] ×3 | 28V DC, 75A continuous each | TR1→DC Bus1, TR2→DC Bus2, TR3→Battery Bus/DC Bus2 |
| [[Battery]] Main + Aux | 22–30V, 48Ah each | 60 min combined emergency power |
| [[Battery-Charger]] ×2 | 27.5V constant, up to 65A | Charge mode below 23V |

## 🎮 AC Distribution & Protection

| Element | Role |
|---|---|
| [[Bus-Tie-Breakers]] | Link/isolate Transfer Bus 1 & 2 |
| [[CBTR]] | Parallels the 3 TRs, opens on G/S capture or Bus Transfer Switch OFF |
| [[Bus-Transfer-Switch]] | AUTO / OFF override of automatic bus transfer |
| [[Transfer-Bus-Warning-Lights]] | GEN OFF BUS / SOURCE OFF / TRANSFER BUS OFF |

## 🛩 Standby & Battery System

| Element | Role |
|---|---|
| [[SPCU]] | Single-source rule for standby power |
| [[Standby-Power-Switch]] | OFF / AUTO / BAT |
| [[RCCB]] | Parallels batteries onto standby system |
| [[Battery-Switch]] | Cascading bus-loss scenarios |
| [[Battery-Buses]] | Hot Battery Bus (always on) vs Switched Hot Battery Bus (BAT ON) |
| [[Static-Inverter]] | DC → AC for AC Standby Bus |

## ⛽ Load Shedding

| Type | Trigger | Sheds |
|---|---|---|
| Configuration (APU) | APU is only AC source in flight | All galley buses |
| Overcurrent | GCU/AGCU overcurrent | Galley & main buses (config-dependent) |
| Command (APU) | High APU EGT | Galley first, then main buses |

## 🌬 No-AC-Power Baseline

See [[07-No-AC-Power-Reference]] for the full table of what remains available with zero AC power.

---
See also: [[Fuel/Home]] · [[Fuel/Quick-Reference/Key Numbers]] · [[Fuel/Quick-Reference/Warning Lights]] · [[Comparison]] · [[Fuel/Quick-Reference/New Abbreviations]]
