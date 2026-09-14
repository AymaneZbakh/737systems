---
tags: [air-conditioning, component, packs, ACM]
system: Air Conditioning
parent: "[[02-Air-Conditioning/Air Conditioning System]]"
---

# ❄️ Air Conditioning Packs

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|Air Conditioning]] | [[Ram Air|Ram Air →]]

> [!abstract] Overview
> Two air-conditioning Packs convert hot, high-pressure bleed air into cool, low-pressure conditioned air for the cabin. Main components: Flow Control & Shutoff Valve (FCSV), Air Cycle Machine (ACM), Primary & Secondary Heat Exchangers.

---

## ⚙️ Pack Operation — Step by Step

| Step | Process |
|------|---------|
| 1 | Hot bleed air enters via **FCSV** (Flow Control & Shutoff Valve) |
| 2 | Air splits: **Cooling Cycle Flow** + **Cooling Cycle Bypass** |
| 3 | Cooling Cycle → **Primary Heat Exchanger** (cooled by ram air) |
| 4 | **ACM Compressor** compresses partially cooled air → gains heat |
| 5 | Air goes to **Secondary Heat Exchanger** → cooled again by ram air |
| 6 | **ACM Turbine** expands air → temperature drops significantly |
| 7 | Cold air mixes with **Cooling Cycle Bypass** → regulated output temp |

```
BLEED IN ──[FCSV]──┬─── COOLING CYCLE BYPASS ───────────────┐
                   │                                          │
              PRIMARY HX ◄─ RAM AIR                          │
                   │                                          │
           ACM COMPRESSOR ──► (gains heat)                   │
                   │                                          │
             SECONDARY HX ◄─ RAM AIR                         │
                   │                                          │
            ACM TURBINE ──► (temp drops)                     │
                   │                                          ▼
                   └──────────────────────────► MIX ──► OUTPUT
```

---

## 📋 FCSV — Flow Control & Shutoff Valve

| Switch Position | Flow Rate | Notes |
|----------------|-----------|-------|
| AUTO (2 packs) | **55 lb/min** | Normal |
| HIGH | **100 lb/min** | Manual HIGH selection |
| AUTO (1 pack, flaps up in-flight) | **80 lb/min** | Auto HIGH |
| AUTO (1 pack + APU bleed ON, both ENG bleed OFF) | **80 lb/min** | Auto HIGH regardless of flap/ground |
| OFF | 0 | Spring-loaded closed (BAT BUS electrically controlled, pressure actuated) |

> [!note] FCSV Characteristics
> Spring-loaded **CLOSED**. Electrically controlled (BAT BUS) and pressure actuated. If both pack switches OFF → no fresh air into cabin → cabin slowly depressurises.

---

## 🌡️ Overheat Limits & Pack Trip-Off

| Location | Overheat Temp | Action |
|----------|--------------|--------|
| ACM Compressor | **199°C / 390°F** | FCSV closes, PACK light |
| ACM Turbine | **99°C / 210°F** | FCSV closes, PACK light |
| Pack Discharge | **121°C / 250°F** | FCSV closes, PACK light |

> [!warning] Pack Trip-Off Recovery
> Pack can be restored after cooling down by pressing **TRIP RESET**. QRH instructs turning ZONE TEMP selectors to a **higher** temperature before reset — this reduces ACM workload and prevents another trip.

---

## 💡 PACK Light Logic

| PACK Light State | Meaning |
|-----------------|---------|
| Illuminated (steady) | Pack trip-off (overheat) OR pack control failure |
| ON RECALL | Failure of primary or standby pack control |
| Illuminated + cannot be reset | Both primary & standby pack controls failed — pack runs until overheat trip-off |

---

## 🔗 Related
- [[02-Air-Conditioning/Air Conditioning System|Air Conditioning System]]
- [[Ram Air|Ram Air]]
- [[Pack Zone Controllers|Pack/Zone Controllers]]
- [[Zone Temperature Control|Zone Temperature Control]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
