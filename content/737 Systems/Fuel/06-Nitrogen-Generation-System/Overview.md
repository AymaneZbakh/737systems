---
tags: [fuel, ngs, flammability, overview]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../05-Fueling-Defueling-Ground-Transfer/Overview|← Previous]] | [[../Summary/System Overview|Next →]]

# 🌬 06 — Nitrogen Generation System (NGS)

> [!abstract] Overview
> The NGS converts bleed air into nitrogen-enriched air (NEA) and delivers it to the center tank to reduce fuel vapor flammability. It requires no flight crew action and provides no flight deck indications — only a wheel-well operability indicator.

## 🌬 What It Does

| Parameter | Detail |
|---|---|
| Converts | Bleed air (left side) → nitrogen-enriched air (NEA) |
| Delivered to | Center fuel tank |
| Effect | Decreases O₂ level in center tank by ≈ **12%** — sufficient to prevent ignition of fuel vapor |
| Crew action required | **None** — fully automatic, transparent to crew |
| Flight deck indication | **None** |
| Indicator location | Main wheel well, adjacent to APU fire control panel |

> [!note] Why NGS Exists
> Installed after the 737 Classic and 747 TWA 800 mid-air explosions, both probably caused by **ignited fuel vapors in the center tank** from overheating center fuel pumps running dry.

## ⏱ Operating Logic

| Phase | NGS State |
|---|---|
| After take-off through climb/cruise/descent/landing | **Running** |
| Taxi-in after landing | Running briefly, then shuts down |
| Center tank full | Float valve stops NEA flow into the tank |

## 🛑 Automatic Shutdown Conditions

> [!warning] NGS Shuts Down Automatically For
> - Aircraft on the ground and not in test mode (air-ground sensor = ground)
> - Either engine not running in flight (in-flight engine shutdown)
> - Fire or smoke detected in the cargo hold or main deck areas
> - Left air conditioning pack overheat
> - Center tank refueling valve open

> [!note] Dispatch With NGS Inoperative
> Fuel tanks are primarily protected by **precluding ignition sources**, so dispatch with the NGS inoperative is acceptable under **MEL** procedures.

## 💡 Indicator Lights

| Light | Color | Meaning |
|---|---|---|
| OPERATIONAL | Green | NGS fully operational |
| DEGRADED | Blue | NGS operational, but in a degraded/temporarily serviceable condition |
| INOPERATIVE | Amber | NGS inoperative |
| *(No lights illuminated)* | — | Also indicates NGS inoperative |

## 🧭 Components in This Section

| Page | Summary |
|---|---|
| [[Components/NGS-Operation\|NGS Operation]] | Bleed air conversion, shutdown logic, MEL note |
| [[Components/NGS-Indicator-Lights\|NGS Indicator Lights]] | OPERATIONAL / DEGRADED / INOPERATIVE detail |
| [[Components/NGS-Deactivated-Variant\|NGS Deactivated Variant]] | CN-RNP–ROR partial install / deactivation |

> [!info] Related
> See [[../01-Fuel-Storage-and-Feed/Components/Center-Tank|Center Tank]] for the tank NGS protects, and [[../Quick-Reference/Variant Comparison|Variant Comparison]] for which tails have NGS installed.
