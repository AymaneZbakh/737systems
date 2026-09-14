---
tags: [pressurisation, system, air-systems]
system: Pressurisation
parent: Home
---

# 🔵 Pressurisation System

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|← Air Conditioning]]

> [!abstract] Overview
> The Pressurisation System maintains a safe cabin altitude by controlling how much air escapes through the Outflow Valve. Two Cabin Pressure Controllers (CPCs) manage the system automatically. Manual control is available via the Outflow Valve toggle switch.

---

## 🗺 Pressurisation Control Flow

```
CPCs (1 & 2)  ←── ADIRUs (baro/non-corrected alt)
     │         ←── Air/Ground sensors
     │         ←── Throttle position (via SMYD)
     │         ←── Calibrated airspeed
     ↓
OUTFLOW VALVE MOTORS
  ├── VALVE MOTOR (CPC 1)   ← AUTO/ALTN mode
  ├── VALVE MOTOR (CPC 2)   ← AUTO/ALTN mode
  └── VALVE MOTOR (MANUAL)  ← Flight deck toggle (BAT BUS)
         ↓
    OUTFLOW VALVE
   (below right stabiliser)
         ↓
   Cabin pressure controlled
```

---

## 📋 System Quick Facts

| Parameter | Value |
|-----------|-------|
| Number of CPCs | **2** (identical, redundant) |
| CPC power supply | DC BUS #1 and DC BUS #2 |
| CPC roles | Swap each flight (AUTO ↔ ALTN) |
| OFV motors | **3** (CPC1, CPC2, Manual) |
| OFV location | Below right horizontal stabiliser |
| OFV manual power | **BAT BUS** |
| Manual mode travel time | **20 seconds** (full travel — faster than auto) |
| OFV safety close | Cabin alt > **14,500 ft** (CPC control only) |
| Cabin rate target | **≤ 750 FPM** |

---

## 📐 Pressurisation Schedule

| Selected FLT ALT | Max Diff Pressure |
|-----------------|------------------|
| ≤ FL280 | **7.45 psi** |
| FL280 – FL370 | **7.80 psi** |
| > FL370 | **8.35 psi** (BBJ: 8.99 psi) |

> [!note] Schedule Design Intent
> The schedule ensures cabin altitude reaches a maximum of **8,000 ft** at cruise at FL280, FL370, and FL410 — provided CRZ ALT = selected FLT ALT.

> [!tip] Step Climbs — Use Highest Expected FLT ALT
> Setting intermediate FLT ALT values during step climbs causes higher cabin altitudes and schedule changes. The FCTM recommends selecting the **highest expected cruising flight level** before departure.

---

## 🔵 Flight Phases

| Phase | System Behaviour |
|-------|----------------|
| Ground | Cabin begins to pressurise at higher power settings (gradual transition) |
| Liftoff | Pressurisation begins in earnest |
| Climb | Cabin altitude rate-controlled, normally reaches 8,000 ft at certified ceiling of 41,000 ft |
| Cruise | Cruise mode activates when aircraft climbs within **0.25 psi** of selected FLT ALT |
| Descent | Scheduled descent — press stays for possible air turn-back |
| Landing | Cabin slightly pressurised so rapid altitude changes cause minimum pressure change |
| Taxi-in | Cabin slowly depressurises |

---

## 💡 Warning & Status Lights

| Light | Colour | Condition |
|-------|--------|-----------|
| AUTO FAIL | Amber | CPC failure, DC power lost, controller fault, OFV control fault, excess diff press (>8.75 psi), excess cabin rate (>2000 FPM), high cabin alt (>15,800 ft) |
| ALTN | Amber/Green | Backup CPC controlling pressurisation |
| OFF SCHED DESCENT | Amber | Aircraft descending before reaching FLT ALT window altitude |
| MANUAL | White | Pressurisation mode selector in MAN position |

---

## 🔧 Pressurisation System Status Table

| AUTO FAIL | ALTN | MANUAL | Status |
|-----------|------|--------|--------|
| Off | Off | Off | **Normal** automatic operation |
| Amber | Off | Off | Single CPC failure — backup CPC controlling |
| Off | Amber | Off | ALTN manually selected — backup CPC controls, AUTO FAIL extinguishes |
| Amber | Amber | Off | **Both CPCs failed** — automatic control lost |
| Off | Off | Green | Outflow Valve **manually controlled** |

---

## 🚨 Controllable vs Uncontrollable Cabin

> [!warning] Uncontrollable Cabin (Boeing FOTB Definition)
> The cabin is **uncontrollable** when ANY of these is true:
> | Condition | Mode |
> |-----------|------|
> | Cabin altitude rate > 750 FPM | AUTO or ALTN |
> | Cabin altitude rate cannot be controlled manually | Manual |
> | Cabin altitude **≥ 15,000 ft** | Any — regardless of rate controllability |

---

## 📋 Components

| Component | Page |
|-----------|------|
| Cabin Pressure Controllers | [[Components/CPC]] |
| Outflow Valve | [[Components/Outflow Valve]] |
| Pressurisation Schedule | [[Components/Pressurisation Schedule]] |
| Cabin Pressure Relief System | [[Components/Cabin Pressure Relief System]] |
| FLT ALT & LAND ALT | [[Components/FLT and LAND ALT]] |
| Manual Pressurisation | [[Components/Manual Pressurisation]] |

---

## 🔗 Related
- [[Fuel/Quick-Reference/Key Numbers|Key Numbers]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
- [[Fuel/Summary/System Overview|System Overview]]
