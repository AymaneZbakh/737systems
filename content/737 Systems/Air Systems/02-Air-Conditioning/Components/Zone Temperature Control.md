---
tags: [air-conditioning, component, zone-temp, trim-air]
system: Air Conditioning
parent: "[[02-Air-Conditioning/Air Conditioning System]]"
---

# 🌡️ Zone Temperature Control

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|Air Conditioning]] | [[Air Distribution|← Air Distribution]]

> [!abstract] Overview
> Three cabin zones (CONT CAB, FWD CAB, AFT CAB) each have independent temperature control via Trim Air. Packs output at the coldest zone requirement; warmer zones are heated by trim air injection.

---

## 📋 Zone Summary

| Zone | Selector | Temp Range | Controller |
|------|---------|-----------|------------|
| CONT CAB (Flight Deck) | AUTO / C–W / OFF | 18°C–30°C | R Pack (primary) |
| FWD CAB | AUTO / C–W / OFF | 18°C–30°C | R Pack (FWD zone) |
| AFT CAB | AUTO / C–W / OFF | 18°C–30°C | L Pack (AFT zone) |

---

## ⚙️ Operating Modes

### ✅ Balanced Mode (Normal)

| Condition | Pack Output |
|-----------|------------|
| Both packs operating | Same temperature |
| Pack temp | = Zone requiring **most cooling** |
| Trim air | Heats the 2 warmer zones |

### ⚠️ Unbalanced Mode

> [!warning] Unbalanced Mode
> Triggered when flight deck trim air fails (CONT CAB). A ZONE TEMP light illuminates.

| Pack | Output |
|------|--------|
| L PACK | Controlled to satisfy **flight deck** temperature requirement |
| R PACK | = Cabin zone requiring **most cooling** |

### ⚠️ Unbalanced Average Mode

> [!warning] Unbalanced Average Mode
> Triggered when TRIM AIR switch is OFF **or** either passenger zone temperature fails.

| Pack | Output |
|------|--------|
| L PACK | Controlled to satisfy **flight deck** requirement |
| R PACK | Produces **average** of the two cabin zone temperature requirements |

---

## ⚙️ Trim Air System

| Component | Function |
|-----------|----------|
| Trim Air Modulating Valves | Control amount of trim air entering each zone duct |
| Trim Air Modulating & Shutoff Valve | Master shutoff — closes when TRIM AIR switch OFF |
| TRIM AIR switch OFF | Closes all trim air; one zone OFF removes trim from that zone only; all OFF = L PACK 24°C / R PACK 18°C |

> [!info] Trim Air Shutoff — All Zones OFF
> When **all** selectors OFF: L PACK 24°C/75°F, R PACK 18°C/65°F (measured at pack sensor).

---

## 💡 ZONE TEMP Light

| Trigger | MASTER CAUTION | ON RECALL |
|---------|----------------|-----------|
| CONT CAB | Duct overheat ≥88°C OR failure of both primary & standby temp controls | Failure of primary OR standby temp control |
| FWD/AFT CAB | Duct overheat | Failure of associated zone control |

> [!note] Duct Overheat Recovery
> When duct temp overheat: associated Zone Trim Air Modulating Valve **closes automatically**. To restore: duct must cool below limit + TRIP RESET must be pushed.

---

## 🔗 Related
- [[02-Air-Conditioning/Air Conditioning System|Air Conditioning System]]
- [[Packs|Packs]]
- [[Pack Zone Controllers|Pack/Zone Controllers]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
