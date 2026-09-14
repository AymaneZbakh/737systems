---
tags:
  - home
  - fuel
  - 737
  - fcom
system: Fuel
dg-home: true
dg-publish: true
---

🔗 **Home** | — | [[01-Fuel-Storage-and-Feed/Overview|Next →]]

# ⛽ 737 Fuel System — FCOM Chapter 12

> [!abstract] Overview
> Reference vault for the Boeing 737 **Fuel System** (FCOM Chapter 12: Controls & Indicators / System Description). Covers storage, feed, pumps, crossfeed, shutoff valves, quantity indication, fueling/defueling, and the Nitrogen Generation System (NGS). Aircraft variant callouts (e.g. `CN-RGE`, `CN-RGW`, `CN-RNP`) are Royal Air Maroc fleet sub-types with differing panel hardware — see [[Quick-Reference/Variant Comparison|Variant Comparison]].

## 📚 Section Index

| # | Section | Contents |
|---|---|---|
| 01 | [[01-Fuel-Storage-and-Feed/Overview\|Fuel Storage & Feed]] | Tanks, capacities, feed order, temperature, APU feed |
| 02 | [[02-Fuel-Pumps-and-Suction-Feed/Overview\|Fuel Pumps & Suction Feed]] | Main/center pumps, suction feed, scavenge pump, filter bypass |
| 03 | [[03-Fuel-Crossfeed-and-Shutoff/Overview\|Crossfeed & Shutoff Valves]] | Crossfeed valve, spar/engine/APU shutoff valves |
| 04 | [[04-Fuel-Quantity-Indication/Overview\|Fuel Quantity Indication]] | FQIS, indicators, measuring sticks, alerts |
| 05 | [[05-Fueling-Defueling-Ground-Transfer/Overview\|Fueling, Defueling & Ground Transfer]] | Refuel panel, defueling valve, test gages panel |
| 06 | [[06-Nitrogen-Generation-System/Overview\|Nitrogen Generation System (NGS)]] | NGS operation, indicator lights, deactivated variant |
| — | [[Summary/System Overview\|Summary → System Overview]] | Consolidated cross-system summary table |
| — | [[Quick-Reference/Key Numbers\|Quick Reference]] | Numbers, warning lights, variants, abbreviations |

## 🌳 System Architecture

```
FUEL SYSTEM (Ch. 12)
│
├── STORAGE & FEED
│   ├── Main Tank No.1 (wing box)
│   ├── Main Tank No.2 (wing box)
│   ├── Center Tank (wing root / fuselage)
│   │   └── feeds BOTH engines first, then mains
│   ├── Surge Tanks (1 per main tank, 107 kg / 235 lb)
│   └── APU Fuel Feed (left manifold / suction from Tank 1)
│
├── PUMPS
│   ├── Main Tank Pumps  (x2 per tank)  — 10 psi
│   ├── Center Tank Pumps (x2)          — 23 psi (feeds first)
│   ├── Suction Feed (bypasses pumps)
│   └── Center Tank Fuel Scavenge Jet Pump → Main Tank 1
│
├── CROSSFEED & SHUTOFF
│   ├── Crossfeed Valve (butterfly, DC motor, BAT BUS)
│   ├── Spar Fuel Shutoff Valve (HOT BAT BUS + Shutoff Battery)
│   ├── Engine Fuel Shutoff Valve (BAT BUS, fuel-actuated)
│   └── APU Fuel Shutoff Valve (HOT BAT BUS + Shutoff Battery)
│
├── QUANTITY INDICATION
│   ├── FQIS → FQPU → FMCS / CDS / Refuel Panel
│   ├── Fuel Quantity Indicators (flight deck + refuel panel)
│   ├── Fuel Measuring Sticks (manual backup)
│   └── Alerts: FUEL LOW / FUEL CONFIG / FUEL IMBAL
│
├── FUELING / DEFUELING / GROUND TRANSFER
│   ├── Refueling Panel (R wing leading edge, single point)
│   ├── Manual Defueling Valve
│   ├── Fueling Valves + Valve Position Lights
│   └── Test Gages & Fueling Panel
│
└── NITROGEN GENERATING SYSTEM (NGS)
    ├── Converts bleed air → NEA → Center Tank
    ├── OPERATIONAL / DEGRADED / INOPERATIVE lights
    └── Deactivated on CN-RNP–ROR
```

## 🔢 Key Numbers at a Glance

| Parameter | Value |
|---|---|
| Total usable fuel capacity | 26,025 L / 20,896 kg |
| Main Tank No.1 / No.2 capacity | 4,875 L / 3,915 kg each |
| Center Tank capacity | 16,273 L / 13,066 kg |
| Fuel density (reference) | 0.8029 kg/L |
| Surge tank capacity | 107 kg / 235 lb each |
| Main pump output | 10 psi / 9,071 kg/h (20,000 lb/h) |
| Center pump output | 23 psi / 9,071 kg/h (20,000 lb/h) |
| Centre pump LOW PRESSURE threshold | < 22 psi |
| Main pump LOW PRESSURE threshold | < 4 psi |
| Centre scavenge transfer rate | 100–200 kg/h (220–440 lb/h) |
| Scavenge starts at Main Tank 1 qty | ≈ 1,990 kg / 4,300 lb (half full) |
| FUEL LOW threshold (main tank) | < 907 kg (2000 lb) or < 453 kg (1000 lb) by version |
| FUEL CONFIG center tank threshold | > 726 kg (1600 lb) |
| FUEL IMBAL threshold | > 453 kg (1000 lb) difference |
| Max fuel temperature | 49 °C |
| Min fuel temperature | −43 °C or 3 °C above freeze point |
| FQIS max error | 2.5% (in flight) |
| Center tank scavenge float trigger | ~half full Main Tank 1 |
| Suction defuel — eligible tank | Main Tank No. 2 only |

> [!tip] Navigation
> Every page carries a breadcrumb at the top: `🔗 [[Home]] | [[Previous]] | [[Next →]]`. Use [[Quick-Reference/Key Numbers|Key Numbers]] for a fast lookup table of every limit in this vault.
