---
tags: [bleed-air, component, compressor-stage]
system: Bleed Air
parent: "[[01-Bleed-Air-System/Bleed Air System]]"
---

# ⚙️ 5th & 9th Stage Bleed Air

🔗 [[Home - Air Systems]] | [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]

> [!abstract] Overview
> Bleed air is extracted from both the 5th and 9th compressor stages. Stage selection is automatic, based on engine N1.

---

## 📋 Stage Operation

| N1 Range | Active Stage | Regulated By | Approx. Duct Pressure |
|----------|-------------|--------------|----------------------|
| 20–26% | 9th (unregulated) | — | Varies |
| 26–47% | 9th (regulated) | High Stage Valve | **32 psi ±6** |
| 47–54% | Transitioning | — | Varies |
| > 54% | 5th (regulated) | PRSOV | **42 psi ±8** |

> [!note] Crossover Timing
> The crossover from 9th to 5th stage occurs at slightly different N1 for left and right sides — this is normal and causes the common "duct pressure split" seen in cruise.

---

## 🔴 Failure Modes

> [!warning] 5th Stage Check Valve Failure
> FAA issued an emergency AD in 2020 after corroded 5th stage check valves failed to close at flight idle. This allowed reverse flow (9th → 5th), causing engine failure that could not be restarted.

| Scenario | Result |
|----------|--------|
| High stage valve fails to close at high thrust | BLEED TRIP-OFF may occur |
| Wing anti-ice use above FL350 | BLEED TRIP-OFF (excessive demand → high-stage valve opens early → over-temp) |
| Above FL250 | Engine cannot over-pressure the duct (only over-temp risk remains) |

---

## 🔗 Related
- [[01-Bleed-Air-System/Bleed Air System|Bleed Air System]]
- [[PRSOV|PRSOV]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
