---
tags: [bleed-air, component, PRSOV, valve]
system: Bleed Air
parent: "[[01-Bleed-Air-System/Bleed Air System]]"
---

# ⚙️ PRSOV — Pressure Regulator and Shutoff Valve

🔗 [[Home - Air Systems]] | [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]] | [[Precooler →]]

> [!abstract] Overview
> The PRSOV is a butterfly-type valve that controls bleed air flow to the system. It regulates pressure and temperature limits, and acts as a shutoff in abnormal conditions.

---

## 📋 Quick Facts

| Parameter | Value |
|-----------|-------|
| Valve type | Butterfly |
| Pressure limit | **42 psi** |
| Temperature limit | **232°C / 450°F** |
| Actuation | DC activated + Pressure operated |
| Fail-safe position | Spring-loaded **CLOSED** |

---

## 🔌 Electrical / Pneumatic Logic

| Control Type | Detail |
|-------------|--------|
| Electrical | DC powered — signals solenoid to OPEN |
| Pneumatic | Air pressure regulates valve position once open |
| No bleed pressure | Valve stays closed (spring-loaded) |

---

## 🔴 PRSOV Closes When

> [!warning] Automatic Closure Conditions
> | Trigger | Reason |
> |---------|--------|
> | FIRE SWITCH pulled | Fire protection |
> | Engine Bleed Air Switch OFF | Crew selection |
> | BLEED TRIP-OFF | Over-temp >254°C or over-pressure >220 psi |
> | Engine starting (ENG 1 VALVE OPEN) | ENG 1 PRSOV closes during start |

---

## 🔗 Related
- [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]
- [[Precooler|Precooler & PCV]]
- [[5th-9th Stage Bleed|5th & 9th Stage Bleed]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
