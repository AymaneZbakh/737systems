---
tags: [home, electrical, 737]
---

# ⚡ 737 Electrical System — Study Vault

> [!abstract] Overview
> This vault documents the 737 electrical power generation, distribution, standby power, and protection systems, rebuilt from training slide material. Navigate using the index below or jump straight into [[01-Electrical-Basics]].

## 📚 Section Index

| # | Section | Contents |
|---|---------|----------|
| 01 | [[01-Electrical-Basics]] | AC/DC basics, 2 governing principles, battery fundamentals |
| 02 | [[02-Power-Sources]] | [[IDG]], [[APU-Generator]], [[Battery]], [[Battery-Charger]] |
| 03 | [[03-Power-Distribution]] | [[GCU]], [[BPCU]], [[AGCU]], [[Transformer-Rectifier]], [[PDP]] |
| 04 | [[04-AC-Power-System]] | [[Bus-Transfer-Switch]], [[Bus-Tie-Breakers]], [[CBTR]], [[Transfer-Bus-Warning-Lights]], [[Ground-Power]], [[Ground-Service]] |
| 05 | [[05-DC-Standby-Power-System]] | [[SPCU]], [[Standby-Power-Switch]], [[RCCB]], [[Battery-Switch]], [[Battery-Buses]], [[Static-Inverter]] |
| 06 | [[06-Load-Shedding-and-Protection]] | [[Auto-Load-Shedding]], [[CAB-UTIL-Switch]], [[IFE-PASS-SEAT-Switch]] |
| 07 | [[07-No-AC-Power-Reference]] | Systems available with **no AC power**, [[Circuit-Breakers]] |
| — | [[Electrical/Summary/System Overview]] | Consolidated cross-system summary table |
| — | [[Electrical/Quick-Reference/Key Numbers]] · [[Electrical/Quick-Reference/Warning Lights]] · [[Comparison]] · [[Electrical/Quick-Reference/New Abbreviations]] | Quick reference |

## 🌳 System Architecture

```text
737 ELECTRICAL SYSTEM
│
├── AC POWER SOURCES (115V, 3-phase, 400Hz)
│   ├── IDG 1 ─── GCU 1 ─── GCB 1 ──┐
│   ├── IDG 2 ─── GCU 2 ─── GCB 2 ──┤
│   ├── APU Gen ─ AGCU ──── APB ────┼──> AC TRANSFER BUS 1 <──BTB1──BTB2──> AC TRANSFER BUS 2
│   └── Ground Power ── EPC ────────┘         │                                    │
│                                       MAIN BUS 1 / GALLEY C&D          MAIN BUS 2 / GALLEY A&B
│                                       GROUND SERVICE BUS 1             GROUND SERVICE BUS 2
│                                       AC STANDBY BUS (via STATIC INVERTER)
│
├── DC POWER SOURCES (28V)
│   ├── TR 1 ── DC BUS 1
│   ├── TR 2 ── DC BUS 2
│   ├── TR 3 ── BATTERY BUS / DC BUS 2 (parallel via CBTR)
│   ├── MAIN BATTERY ── MAIN BAT CHRG
│   └── AUX BATTERY ── AUX BAT CHRG
│
└── STANDBY POWER SYSTEM (controlled by SPCU)
    ├── AC STANDBY BUS
    ├── DC STANDBY BUS
    ├── BATTERY BUS
    ├── SWITCHED HOT BATTERY BUS (BAT switch ON)
    └── HOT BATTERY BUS (always powered)
```

## 🔢 Key Numbers at a Glance

| Parameter | Value |
|---|---|
| AC system voltage | 115V, 3-phase, 400Hz |
| DC system voltage | 28V |
| IDG output | 90 KVA |
| IDG constant speed | 24,000 RPM |
| APU Generator output | 90 KVA up to FL320, linear decrease to 66 KVA at FL410 |
| APU starter-generator speed | 12,000 RPM |
| Ground Power output | 90 KVA |
| Ground Power receptacle rating | 115/200V, 400 Hz |
| TR continuous load rating | 75 A each |
| Normal TR1/TR2 load | 16–20 A |
| Normal TR3 load | 9–14 A |
| Battery Charger (TR mode) output | Constant 27.5V, up to 65 A |
| Battery Charger charge threshold | Battery voltage < 23V |
| Battery voltage range | 22–30V |
| Battery capacity | 48 Ah each |
| Total emergency power (both batteries) | 60 minutes (30 min if single battery) |
| APU start battery drain | ≈6.7 Ah / 4.2 min per 60s start attempt |
| IDG disconnect trigger (oil temp) | 182°C / 363°F |
| Standby Pwr Off voltage threshold | <100V AC / <17.5V DC for >2s |
| BAT DISCHARGE trip thresholds | 5A/95s · 15A/25s · 100A/1.2s |

> [!tip] Navigation
> Every page carries a breadcrumb (`🔗 [[Home]] | [[Previous]] | [[Next →]]`) — use it to move sequentially through the vault, or jump directly via the tables above.
