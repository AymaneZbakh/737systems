---
tags: [bleed-air, component, isolation-valve]
system: Bleed Air
parent: "[[01-Bleed-Air-System/Bleed Air System]]"
---

# ⚙️ Isolation Valve

🔗 [[Home - Air Systems]] | [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]

> [!abstract] Overview
> The Isolation Valve separates the bleed system into Left and Right manifolds. Normally closed to prevent total system loss from a single duct failure.

---

## 📋 Quick Facts

| Parameter | Value |
|-----------|-------|
| Normal position | **CLOSED** |
| Power supply | Transfer Bus #1 (AC) |
| AC power lost | Valve **stays in current position** |
| Valve type | Butterfly |

---

## ⚙️ Automatic Opening Logic

| Condition | Result |
|-----------|--------|
| Switch in AUTO + any **corner switch** placed to OFF | Opens automatically |
| BLEED TRIP-OFF | Does **NOT** change position |
| PACK light | Does **NOT** change position |

> [!note] Corner Switches
> The 4 corner switches are: L PACK, R PACK, L ENG BLEED, R ENG BLEED. Placing any one to OFF with Isolation Valve switch in AUTO causes the valve to open.

---

## 🔧 Special Uses

| Use Case | Requirement |
|----------|------------|
| Engine cross-bleed start | Isolation valve must be **OPEN** |
| Single-engine operation | Opens to share bleed source across both manifolds |

---

## 🔗 Related
- [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]
- [[APU Bleed|APU Bleed]]
- [[Ground Pneumatic Connector|Ground Pneumatic Connector]]
