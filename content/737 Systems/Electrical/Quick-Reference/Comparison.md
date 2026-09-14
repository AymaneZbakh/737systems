---
tags: [electrical, quick-reference, comparison]
---

🔗 [[Fuel/Home]] | [[Electrical/Quick-Reference/Warning Lights|← Previous]] | [[Electrical/Quick-Reference/New Abbreviations|Next →]]

# ⚖️ Side-by-Side Comparisons

> [!abstract] Overview
> Key decision points in the electrical system, compared side-by-side.

## 🎛 Standby Power Switch: AUTO vs BAT vs OFF

| Position | AC/DC Standby Bus Power Source | Static Inverter |
|---|---|---|
| **OFF** | None | Not powered |
| **AUTO** | XFR Bus 1 / TR1,2,3 → switches to battery if Transfer Bus 1 or DC Bus 1 lost | Powered as needed |
| **BAT** | Battery only | Powered from battery |

## 🔋 Battery Switch: BAT OFF Scenarios

| Scenario | Buses Lost |
|---|---|
| Normal AC power, Standby in AUTO | Battery Bus, Switched Hot Battery Bus |
| Battery is only source of power | Battery Bus, Switched Hot Battery Bus, AC Standby Bus, DC Standby Bus, Static Inverter |
| Standby power in BAT | Switched Hot Battery Bus only |

## 🔌 Bus Transfer Switch: AUTO vs OFF

| Aspect | AUTO | OFF |
|---|---|---|
| Bus Tie Breakers | Open normally; close automatically on single-source condition | **Locked open** — Transfer Bus 1 isolated from Transfer Bus 2 |
| DC Cross Bus Tie Relay | Normally closed (TRs share load) | **Open** — DC Bus 1 isolated from DC Bus 2 |
| TR3 source | Shares load via CBTR | Isolated from Transfer Bus 1 — powered by Transfer Bus 2 |

## 🔧 AC Power Sources: Output Comparison

| Source | Rated Output | Altitude-dependent? |
|---|---|---|
| IDG | 90 KVA | No |
| APU Generator | 90 KVA → 66 KVA | Yes — decreases above FL320 |
| Ground Power | 90 KVA | No |

## 💡 TR Unit Light: Ground vs In-Flight Logic

| Phase | Trigger |
|---|---|
| On ground | **Any** TR failed |
| In flight | TR1 failed **or** TR2 **and** TR3 both failed |

---
See also: [[Fuel/Home]] · [[Electrical/Quick-Reference/Warning Lights]] · [[Electrical/Quick-Reference/New Abbreviations]]
