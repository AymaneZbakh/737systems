---
tags: [quick-reference, warning-lights, cautions]
parent: Home
---

# 💡 Warning Lights — All Air Systems

🔗 [[Home - Air Systems]] | [[Air Systems/Quick-Reference/Key Numbers|← Key Numbers]] | [[Air Systems/Quick-Reference/New Abbreviations|Abbreviations →]]

> [!abstract] Overview
> All warning, caution, and advisory lights related to Air Systems, grouped by system with conditions and crew actions.

---

## 🌬 Bleed Air System Lights

| Light | Colour | Illuminates When | Key Action |
|-------|--------|-----------------|-----------|
| **DUAL BLEED** | Amber | APU bleed OPEN + (ENG 1 bleed ON **or** ENG 2 bleed ON + Isolation Valve OPEN) | Operate engines at **IDLE thrust only** |
| **BLEED TRIP-OFF** | Amber | Over-temp >254°C or over-pressure >220 psi → PRSOV auto-closes | TRIP RESET after temps normalise |
| **WING-BODY OVERHEAT** | Amber | Bleed duct leak sensed in wing/body area | Do **NOT** use Wing Anti-Ice; watch for opposite side failures |

> [!warning] DUAL BLEED — Idle Thrust
> Engine bleed air at higher thrust could back-pressure the APU and cause damage. Keep engines at idle when DUAL BLEED is on.

---

## ❄️ Air Conditioning System Lights

| Light | Colour | Illuminates When | Key Action |
|-------|--------|-----------------|-----------|
| **PACK** | Amber | Pack trip-off (overheat) OR pack control failure | Push TRIP RESET after cooling; turn zone temps higher first |
| **PACK** (on recall) | Amber | Failure of primary or standby pack control | Monitor; pack still operating |
| **ZONE TEMP** (CONT CAB) | Amber | Duct overheat ≥88°C OR failure of both primary & standby temp controls | Zone Trim Air valve auto-closes; TRIP RESET when cooled |
| **ZONE TEMP** (FWD/AFT) | Amber | Duct overheat OR associated zone control failure | — |
| **ZONE TEMP** (on recall) | Amber | Failure of primary or standby temp control | — |
| **OFF** (equip cooling) | Amber | Insufficient airflow through equipment cooling system | Select alternate fan; if on ground, horn sounds in nose wheel well |
| **RAM DOOR FULL OPEN** | Blue | Ram air inlet at full open (ground / flaps not fully retracted) | Normal; if illuminates in flight with flaps up → possible blocked HX |

> [!note] Equipment Cooling OFF Light
> Disruption of equipment cooling can **signal impending pressurisation problems** — monitor closely.

---

## 🔵 Pressurisation System Lights

| Light | Colour | Illuminates When | Extinguishes When |
|-------|--------|-----------------|-----------------|
| **AUTO FAIL** | Amber | DC power lost / controller fault / OFV fault / diff press >8.75 psi / rate >2,000 FPM / cabin alt >15,800 ft | ALTN light comes on (backup CPC) |
| **ALTN** | Amber | Backup CPC controlling pressurisation | FLT ALT reset / aircraft climbs / MAN selected / aircraft lands |
| **OFF SCHED DESCENT** | Amber | Aircraft descends before reaching FLT ALT window | FLT ALT reset / aircraft climbs / MAN mode / aircraft lands |
| **MANUAL** | White | Pressurisation Mode Selector in MAN | Selector moved to AUTO |

### Pressurisation System Status

| AUTO FAIL | ALTN | MANUAL | Meaning |
|-----------|------|--------|---------|
| Off | Off | Off | ✅ Normal automatic operation |
| 🟡 On | Off | Off | Single CPC failure — backup CPC controlling |
| Off | 🟡 On | Off | ALTN manually selected — backup CPC active, AUTO FAIL extinguishes |
| 🟡 On | 🟡 On | Off | ⚠️ Both CPCs failed — no automatic control |
| Off | Off | ⬜ On | Manual OFV control active |

> [!warning] Both CPCs Failed
> When AUTO FAIL and ALTN both illuminate, automatic pressurisation control is lost. Manual control of the Outflow Valve is required immediately. See [[03-Pressurisation/Components/Manual Pressurisation|Manual Pressurisation]].

---

## 🆚 Comparison: Controllable vs Uncontrollable Cabin

| Condition | Controllable? | Notes |
|-----------|-------------|-------|
| Rate >750 FPM in AUTO/ALTN | ❌ UNCONTROLLABLE | — |
| Rate cannot be manually controlled | ❌ UNCONTROLLABLE | — |
| Cabin alt ≥15,000 ft | ❌ UNCONTROLLABLE | Regardless of rate — too long to descend to 10,000 ft |
| Rate ≤750 FPM, cabin alt <15,000 ft | ✅ Controllable | Normal bounds |

---

## 🔗 Related
- [[Air Systems/Quick-Reference/Key Numbers|Key Numbers]]
- [[Air Systems/Quick-Reference/New Abbreviations|Abbreviations]]
- [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]
- [[02-Air-Conditioning/Air Conditioning System|Air Conditioning System]]
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
