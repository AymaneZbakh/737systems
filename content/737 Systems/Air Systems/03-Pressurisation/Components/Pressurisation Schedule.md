---
tags: [pressurisation, component, schedule, diff-pressure]
system: Pressurisation
parent: "[[03-Pressurisation/Pressurisation System]]"
---

# 📐 Pressurisation Schedule

🔗 [[Home - Air Systems]] | [[03-Pressurisation/Pressurisation System|Pressurisation]]

> [!abstract] Overview
> The pressurisation schedule defines maximum differential pressure limits based on selected FLT ALT. It is designed to maintain max cabin altitude of 8,000 ft and to maximise cabin structure service life.

---

## 📋 Differential Pressure Limits

| Selected FLT ALT | Max Diff Pressure |
|-----------------|------------------|
| ≤ FL280 | **7.45 psi** |
| FL280 – FL370 | **7.80 psi** |
| > FL370 | **8.35 psi** (BBJ: 8.99 psi) |

---

## 📊 Cabin/Flight Altitude Placard

| Cabin ALT | Land ALT | FLT ALT |
|-----------|---------|---------|
| 2,000 ft | — | < FL160 |
| 4,000 ft | — | FL220 |
| 6,000 ft | — | FL260 |
| 8,000 ft | — | FL320 |
| — | — | FL410 |

---

## 🔄 Step Climb Example

> [!note] Step Climb Scenario (FL370 → FL380)
> | Phase | FLT ALT | Diff Press Limit | Cabin ALT |
> |-------|---------|-----------------|-----------|
> | Cruise FL370 | FL370 | 7.80 psi | 8,000 ft |
> | Step climb to FL380 | Reset to FL380 | 8.35 psi | Starts descending |
> | Cruise FL380 | FL380 | 8.35 psi | Would reach 8,000 ft again if step to FL410 |

---

## ⚠️ Step Climb Best Practice

> [!tip] FCTM Recommendation
> Select the **highest expected cruising flight level** in FLT ALT before departure.

| Risk of Intermediate FLT ALT Settings | Consequence |
|---------------------------------------|------------|
| Multiple FLT ALT adjustments | Increases crew workload unnecessarily |
| Intermediate settings | Higher cabin altitudes with each schedule change |
| Forgot to reset FLT ALT during step | Diff press hits max → cabin rate of climb = airplane rate of climb |

---

## 🔗 Related
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
- [[FLT and LAND ALT|FLT ALT & LAND ALT]]
- [[CPC|CPC]]
- [[Fuel/Quick-Reference/Key Numbers|Key Numbers]]
