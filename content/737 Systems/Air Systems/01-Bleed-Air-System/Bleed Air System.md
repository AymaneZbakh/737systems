---
tags: [bleed-air, system, air-systems]
system: Bleed Air
parent: Home
---

# 🌬 Bleed Air System

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|Air Conditioning →]]

> [!abstract] Overview
> The Bleed Air System extracts hot, pressurised air from the engine compressors (or APU) and supplies it to the Air Conditioning and Pressurisation systems, as well as wing anti-ice, engine starters, and other consumers.

---

## ⚙️ System Summary

| Parameter | Value |
|-----------|-------|
| Primary source | Engine bleed (5th & 9th stage) |
| Alternate sources | APU, External Ground Pneumatic |
| Duct material | Insulation blankets + gold coating |
| Max external source pressure | **60 psi** |
| Max external source temperature | **232°C / 450°F** |
| High duct pressure (maintenance) | **> 50 psi** |
| Duct pressure for cross-bleed start | **30 psi** |
| Regulated 9th stage pressure (27–47% N1) | **32 psi ±6** |
| Regulated 5th stage pressure (>54% N1) | **42 psi ±8** |

---

## 🗺 Bleed System Schematic

```
ENGINE 1 BLEED                          ENGINE 2 BLEED
     │                                        │
  [PRSOV]                                 [PRSOV]
     │                                        │
  [PRECOOLER] ◄── Cold Fan Air               │
     │                                        │
LEFT MANIFOLD ──── [ISOLATION VALVE] ──── RIGHT MANIFOLD
     │                                             │
  TO L PACK                          TO R PACK / APU BLEED VALVE
     │                                        │
  [DUCT PRESS                          [PNEUMATIC GROUND
   TRANSMITTER]                          CONNECTOR]
```

---

## 📋 Components

| Component | Function | Page |
|-----------|----------|------|
| PRSOV | Regulates pressure (42 psi) & temperature (232°C) | [[Components/PRSOV]] |
| Precooler | Air-to-air heat exchanger, reduces bleed temp | [[Components/Precooler]] |
| High Stage Valve | Supplies 9th stage at low N1 | [[Components/5th-9th Stage Bleed]] |
| 5th Stage Check Valve | Prevents reverse flow when high-stage open | [[Components/5th-9th Stage Bleed]] |
| Isolation Valve | Separates L & R manifolds | [[Components/Isolation Valve]] |
| APU Bleed | Alternate bleed source on ground/low alt | [[Components/APU Bleed]] |
| Ground Pneumatic Connector | External pneumatic for engine start (APU INOP) | [[Components/Ground Pneumatic Connector]] |
| Duct Pressure Transmitter | Sends pressure indication to A/C panel | [[Components/Duct Pressure Transmitter]] |

---

## 💡 Warning Lights

| Light | Colour | Condition |
|-------|--------|-----------|
| DUAL BLEED | Amber | APU bleed OPEN + ENG 1 bleed ON, or ENG 2 bleed ON + Isolation Valve OPEN |
| BLEED TRIP-OFF | Amber | Over-temp (254°C) or over-pressure (220 psi) → PRSOV auto-closes |
| WING-BODY OVERHEAT | Amber | Bleed duct leak detected in wing/body area |

> [!warning] DUAL BLEED
> When DUAL BLEED illuminates, operate engines at **IDLE thrust only** — engine bleed could back-pressure the APU and cause damage.

> [!warning] WING-BODY OVERHEAT
> Watch for subsequent A/C or PRESS failures on the **opposite side**. Do **not** use Wing Anti-Ice.

---

## 🔢 N1 Stage Crossover Summary

| N1 Range | Active Stage | Regulated By | Duct Pressure |
|----------|-------------|--------------|---------------|
| 20–26% | 9th stage (unregulated) | — | Varies |
| 26–47% | 9th stage (regulated) | High Stage Valve | ~32 psi ±6 |
| 47–54% | 5th stage (unregulated) | — | Transitioning |
| >54% | 5th stage (regulated) | PRSOV | ~42 psi ±8 |

> [!note] Duct Pressure Minimums
> During T/O, climb, and cruise: **above 18 psi**. Just after top of descent: **above 10 psi**. Below these values → maintenance required.

---

## 🔗 Related Pages
- [[Components/PRSOV|PRSOV]]
- [[Components/Precooler|Precooler & PCV]]
- [[Components/5th-9th Stage Bleed|5th & 9th Stage Bleed]]
- [[Components/Isolation Valve|Isolation Valve]]
- [[Components/APU Bleed|APU]]
- [[Components/Duct Pressure Transmitter|Duct Pressure Transmitter]]
- [[Fuel/Quick-Reference/Key Numbers|Key Numbers]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
