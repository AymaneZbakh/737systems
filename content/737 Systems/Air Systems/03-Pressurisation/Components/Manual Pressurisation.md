---
tags: [pressurisation, component, manual, abnormal]
system: Pressurisation
parent: "[[03-Pressurisation/Pressurisation System]]"
---

# 🔧 Manual Pressurisation Control

🔗 [[Home - Air Systems]] | [[03-Pressurisation/Pressurisation System|Pressurisation]] | [[Outflow Valve|← OFV]]

> [!abstract] Overview
> Manual control of the Outflow Valve is available at all times via the toggle switch on the overhead panel. Manual mode operates faster than auto modes and adds crew workload.

---

## ⚠️ Non-Normal Conditions Requiring Manual

| Condition | Reason Manual May Be Needed |
|-----------|-----------------------------|
| Cabin Altitude Warning / Rapid Decompression | Emergency |
| Tail Strike | Structural |
| PACK, BLEED TRIP-OFF, WING-BODY OVERHEAT | Reduced pressurisation source |
| AUTO FAIL + ALTN not available | Both CPCs lost |
| Loss of AC Power (DC BUS 1 & 2 dead) | CPC motors powered from DC buses |
| Landing Gear Won't Retract | Air-ground sensor stuck in ground → CPCs open OFV at thrust reduction |
| Cabin Temperature Hot | Thermal/pressure management |
| Unscheduled Pressurisation Change (>750 FPM) | Excessive rate |

---

## ⚙️ Manual OFV Key Facts

| Characteristic | Detail |
|---------------|--------|
| Speed | **Faster** than auto (20 sec full travel) — designed for evacuation |
| Power | BAT BUS — available even on standby power |
| Toggle switch | Hold OPEN or CLOSE — **do not hold > 1 second** |
| OFV position varies | Throughout flight — depends on bleed supply & air leakage |
| After thrust change | OFV position likely needs adjustment |
| With TAI/WAI use | OFV position may need changing |

> [!warning] Manual Control Adds Workload
> Focus on all available indications: cabin differential pressure, cabin altitude, and cabin rate simultaneously. When cabin is over-pressurised and cabin altitude is below MSL, the indication travels counter-clockwise past 0 towards FL500.

> [!note] Cabin Climb vs Descent — 4000 FPM
> Cabin rate of climb and descent of **4,000 FPM looks identical** on the indicator. Refer to differential pressure and cabin altitude to determine direction.

---

## 📋 Cabin/Flight Altitude Placard

Use the placard beneath the Pressurisation Mode Selector to determine desired cabin altitude for a given Flight Altitude when controlling manually.

| Cabin ALT | FLT ALT |
|-----------|---------|
| 2,000 ft | < FL160 |
| 4,000 ft | FL220 |
| 6,000 ft | FL260 |
| 8,000 ft | FL320 |
| — | FL410 |

---

## 🔗 Related
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
- [[Outflow Valve|Outflow Valve]]
- [[CPC|CPC]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
