---
tags: [pressurisation, component, FLT-ALT, LAND-ALT]
system: Pressurisation
parent: "[[03-Pressurisation/Pressurisation System]]"
---

# 📡 FLT ALT & LAND ALT

🔗 [[Home - Air Systems]] | [[03-Pressurisation/Pressurisation System|Pressurisation]]

> [!abstract] Overview
> FLT ALT and LAND ALT are set on the overhead pressurisation panel before take-off. They define the maximum differential pressure schedule and landing altitude for the pressurisation system.

---

## 📋 Setting Summary

| Parameter | Range | Increment | Set To |
|-----------|-------|-----------|--------|
| FLT ALT | −1,000 ft to 42,000 ft | 500 ft | Highest expected cruising altitude |
| LAND ALT | −1,000 ft to 14,000 ft | 50 ft | Destination airport elevation |

> [!note] Step Climbs
> If step climbs are expected, set FLT ALT to the **last (highest) CRZ ALT**.

> [!tip] High-Elevation Landings
> When landing at an airfield above **6,000 ft**, a supplementary procedure applies for setting landing altitude.

---

## ⚙️ OFF SCHED DESCENT Logic

| Event | Effect on LAND ALT |
|-------|------------------|
| OFF SCHED DESCENT light illuminates | LAND ALT is discretely set to **departure airport** (for possible air turn-back) |
| FLT ALT reset to current altitude | OFF SCHED DESCENT extinguishes |
| Aircraft climbs again | OFF SCHED DESCENT extinguishes |
| Pressurisation Mode → MAN | OFF SCHED DESCENT extinguishes |
| Aircraft lands | OFF SCHED DESCENT extinguishes |

---

## 💡 HIGH ALT LDG Switch (Certain Models)

> [!info] High Altitude Landing
> Certain models have a HIGH ALT LDG switch. When ON, the **Cabin Altitude Warning is delayed up to 15,200 ft** to enable landings at high-elevation airports without spurious warnings.

---

## 🔗 Related
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
- [[Pressurisation Schedule|Pressurisation Schedule]]
- [[CPC|CPC]]
