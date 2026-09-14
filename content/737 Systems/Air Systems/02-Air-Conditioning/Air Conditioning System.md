---
tags: [air-conditioning, system, air-systems]
system: Air Conditioning
parent: Home
---

# ❄️ Air Conditioning System

🔗 [[Home - Air Systems]] | [[01-Bleed-Air-System/Bleed Air System|← Bleed Air]] | [[03-Pressurisation/Pressurisation System|Pressurisation →]]

> [!abstract] Overview
> The Air Conditioning System conditions bleed air to comfortable temperatures (18°–30°C) and distributes it throughout the cabin, flight deck, and cargo areas. It comprises the Packs, Air Distribution, Zone Temperature Control, and Equipment Cooling subsystems.

---

## 🗺 System Schematic (Simplified)

```
BLEED AIR (L/R Engine or APU)
         │
    [FCSV — Pack Flow Control & Shutoff Valve]
         │
    ┌────┴────────────────────────┐
    │  AIR CONDITIONING PACK      │
    │  ┌──────────────────────┐   │
    │  │ PRIMARY HEAT EXCHG   │◄──┼── RAM AIR
    │  └──────────────────────┘   │
    │         │ Cooling Cycle Flow│
    │  ┌──────┴───────┐           │
    │  │  ACM          │          │
    │  │ Compressor   │          │
    │  │ Turbine      │          │
    │  └──────────────┘           │
    │  ┌──────────────────────┐   │
    │  │ SECONDARY HEAT EXCHG │◄──┼── RAM AIR
    │  └──────────────────────┘   │
    │  [Cooling Cycle Bypass]      │
    └────────────┬────────────────┘
                 │ Cold conditioned air
           [MIX MANIFOLD]
          ┌──────┴───────┐
    TRIM AIR            RISER DUCTS
    (zone heating)       │
                   OVERHEAD DISTRIBUTION
                   CONT CAB / FWD CAB / AFT CAB
```

---

## 📋 Subsystems

| Subsystem | Key Component | Page |
|-----------|--------------|------|
| Packs | ACM, Heat Exchangers, FCSV | [[Components/Packs]] |
| Ram Air | Ram air inlet doors, Deflector door | [[Components/Ram Air]] |
| Pack/Zone Controllers | 2× P/Z Controllers | [[Components/Pack Zone Controllers]] |
| Air Distribution | Mix manifold, Recirc fans, HEPA | [[Components/Air Distribution]] |
| Zone Temp Control | Trim air, 3 zones | [[Components/Zone Temperature Control]] |
| Equipment Cooling | Supply/Exhaust fans, OBD exhaust valve | [[Components/Equipment Cooling]] |
| Ground Conditioned Air | External A/C connector | [[Components/Ground Conditioned Air Connector]] |

---

## 🔢 Key Parameters

| Parameter | Value |
|-----------|-------|
| Temperature range (controllable) | **18°C – 30°C (65°F – 85°F)** |
| Pack normal flow (2 packs) | **55 lb/min** |
| Pack HIGH flow | **100 lb/min** |
| Pack HIGH flow — single pack, flaps up in-flight | **80 lb/min** |
| Recirculation (both fans ON) | ~50% recycled, ~50% fresh |
| ACM compressor overheat limit | **199°C / 390°F** |
| ACM turbine overheat limit | **99°C / 210°F** |
| Pack discharge overheat limit | **121°C / 250°F** |

---

## 💡 Warning Lights

| Light | Condition |
|-------|-----------|
| PACK (amber) | Pack trip-off (overheat) or pack control failure |
| ZONE TEMP (amber) | Duct overheat ≥88°C (CONT CAB) or zone control failure |
| OFF (equip cooling) | Insufficient airflow through equipment cooling |
| RAM DOOR FULL OPEN | Ram air inlet at full open (ground / flaps not retracted) |

---

## 🔗 Related Pages
- [[Components/Packs|Packs]]
- [[Components/Ram Air|Ram Air]]
- [[Components/Pack Zone Controllers|Pack/Zone Controllers]]
- [[Components/Air Distribution|Air Distribution]]
- [[Components/Zone Temperature Control|Zone Temperature Control]]
- [[Components/Equipment Cooling|Equipment Cooling]]
- [[Components/Ground Conditioned Air Connector|Ground Conditioned Air]]
- [[Fuel/Quick-Reference/Key Numbers|Key Numbers]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
