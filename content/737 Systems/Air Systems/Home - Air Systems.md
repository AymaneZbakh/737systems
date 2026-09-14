---
tags: [home, index, boeing-737, air-systems]
---

# ✈ Boeing 737 Air Systems — Obsidian Vault

> [!abstract] Overview
> This vault covers the complete Boeing 737 Air Systems: Bleed Air, Air Conditioning (Packs, Distribution, Temperature), and Pressurisation. Pages are cross-linked for rapid study and reference.

---

## 📚 Section Index

| # | System | Main Page | Key Components |
|---|--------|-----------|---------------|
| 01 | 🌬 Bleed Air System | [[01-Bleed-Air-System/Bleed Air System\|Bleed Air System]] | [[PRSOV]], [[Precooler]], [[Isolation Valve]], [[APU Bleed]] |
| 02 | ❄️ Air Conditioning | [[02-Air-Conditioning/Air Conditioning System\|Air Conditioning]] | [[Packs]], [[Air Distribution]], [[Zone Temperature Control]], [[Equipment Cooling]] |
| 03 | 🔵 Pressurisation | [[03-Pressurisation/Pressurisation System\|Pressurisation]] | [[CPC]], [[Outflow Valve]], [[Cabin Pressure Relief System]] |
| QR | ⚡ Quick Reference | [[Air Systems/Quick-Reference/Key Numbers\|Key Numbers]] | [[Air Systems/Quick-Reference/Warning Lights\|Warning Lights]], [[Air Systems/Quick-Reference/New Abbreviations\|Abbreviations]] |
| SUM | 📋 Summary | [[Air Systems/Summary/System Overview\|System Overview]] | All systems consolidated |

---

## 🏗 System Architecture Tree

```
AIR SYSTEMS
│
├── 01 BLEED AIR SYSTEM
│   ├── Engine Bleed (5th & 9th stage)
│   │   ├── PRSOV (Pressure Regulator & Shutoff Valve)
│   │   ├── Precooler + Precooler Control Valve
│   │   └── High Stage Valve + 5th Stage Check Valve
│   ├── APU Bleed
│   ├── Ground Pneumatic Connector
│   ├── Isolation Valve (L/R manifold separation)
│   └── Duct Pressure Transmitter
│
├── 02 AIR CONDITIONING
│   ├── PACKS (L & R)
│   │   ├── Flow Control & Shutoff Valve (FCSV)
│   │   ├── Air Cycle Machine (ACM)
│   │   ├── Heat Exchangers (Primary & Secondary)
│   │   ├── Ram Air System
│   │   └── Pack/Zone Controllers
│   ├── Air Distribution
│   │   ├── Mix Manifold
│   │   ├── Riser Ducts → Overhead Distribution
│   │   ├── Recirculation Fans (L & R) + HEPA Filters
│   │   └── Ground Conditioned Air Connector
│   ├── Zone Temperature Control
│   │   ├── 3 Zones: CONT CAB / FWD CAB / AFT CAB
│   │   ├── Trim Air Modulating & Shutoff Valve
│   │   └── Balanced / Unbalanced / Unbalanced Average modes
│   └── Equipment Cooling
│       ├── Supply & Exhaust Fans (NORM/ALTN)
│       ├── Overboard Exhaust Valve
│       └── E&E Rack, CDUs, Display Units
│
└── 03 PRESSURISATION
    ├── Cabin Pressure Controllers (CPC 1 & 2)
    ├── Outflow Valve (3 motors: CPC1, CPC2, Manual)
    ├── Pressurisation Schedule (3 diff-press limits)
    ├── Cabin Pressure Relief System
    │   ├── 2× Positive Relief Valves (9.1 psi)
    │   └── 1× Negative Relief Valve (−1.0 psi)
    └── Indication & Warning
        ├── Cabin Altimeter / Diff Press / Rate of Climb
        └── AUTO FAIL / ALTN / OFF SCHED DESCENT lights
```

---

## 🔢 Key Numbers at a Glance

| Parameter | Value | System |
|-----------|-------|--------|
| Max diff pressure (FLT ALT ≤ FL280) | **7.45 psi** | Pressurisation |
| Max diff pressure (FL280–FL370) | **7.80 psi** | Pressurisation |
| Max diff pressure (> FL370) | **8.35 psi** | Pressurisation |
| Positive relief valves open | **9.1 psi** | Press Relief |
| Negative relief valve opens | **−1.0 psi** | Press Relief |
| Cabin altitude warning activates | **10,000 ft** | Pressurisation |
| Cabin altitude = uncontrollable | **≥ 15,000 ft** | Pressurisation |
| AUTO FAIL: high cabin altitude trigger | **15,800 ft** | CPC |
| Cabin rate limit (normal) | **750 FPM** | Pressurisation |
| Uncontrollable rate threshold (AUTO/ALTN) | **> 750 FPM** | Pressurisation |
| PRSOV limits pressure to | **42 psi** | Bleed Air |
| PRSOV limits temperature to | **232°C / 450°F** | Bleed Air |
| Bleed Trip-Off: over-temp | **254°C / 490°F** | Bleed Air |
| Bleed Trip-Off: over-pressure | **220 psi** | Bleed Air |
| Duct pressure: high (maint. required) | **> 50 psi** | Bleed Air |
| Duct pressure for cross-bleed start | **30 psi** | Bleed Air |
| External pneumatic source max | **60 psi / 232°C** | Ground Ops |
| Pack normal flow (2 packs) | **55 lb/min** | Packs |
| Pack HIGH flow | **100 lb/min** | Packs |
| Zone temp range | **18°C–30°C** | Air Cond |
| ACM compressor overheat | **199°C / 390°F** | Packs |
| ACM turbine overheat | **99°C / 210°F** | Packs |
| Pack discharge overheat | **121°C / 250°F** | Packs |
| APU bleed air only (max altitude) | **17,000 ft** | APU |
| APU bleed + electric (max altitude) | **10,000 ft** | APU |
| OFV safety close (cabin alt above) | **14,500 ft** | Pressurisation |
