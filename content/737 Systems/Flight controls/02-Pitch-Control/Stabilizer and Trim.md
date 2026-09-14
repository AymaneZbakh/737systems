---
tags: [B737, pitch, stabiliser, trim, jackscrew]
parent: "[[Pitch Control]]"
---

# Stabiliser & Trim
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Electric pitch trim via single stab trim actuator. Manual backup via trim wheels. Stabiliser movement back-drives trim wheels to provide clear indication of trimming. Two independent brake systems hold stabiliser when not trimming.

---

## System Architecture

```
Electric trim (switches / A/P)
  → Stab Trim Actuator → Gearbox → Jackscrew → Stabiliser

Manual trim (trim wheels)
  → Manual Trim Wheel Cables → Aft Cable Drum → Gearbox → Jackscrew → Stabiliser
```

- Requires power from **Transfer Bus #2**
- Stabiliser moves → **back-drives trim wheels** (crew can see/stop trim)
- Trim wheels offset **90°** — ensures at least one pilot always has leverage

---

## Trim Speeds

| Mode | Condition | Range | Speed |
|------|-----------|-------|-------|
| Main Electric — HIGH | Flaps NOT up | 0.05 – 14.5 units | 0.4 units/sec (Main) / 0.27 units/sec (A/P) |
| Main Electric — SLOW | Flaps up | 3.95 – 14.5 units | 0.2 units/sec (Main) / 0.09 units/sec (A/P) |
| Manual | Any | -0.2 – 16.9 units | — |

> [!info] Unit equivalents
> 1 stab trim unit ≈ **1° stabiliser movement**
> 1 stab trim unit ≈ **15 turns** of manual trim wheel

---

## Trim Wheel Features

- Both control column trim switches must be activated at same time (prevents inadvertent trim)
- A/P disengages if manual trim is applied
- Trim wheels offset 90° to ensure leverage for both pilots

---

## STAB TRIM OVERRIDE Switch

| Position | Behaviour |
|----------|-----------|
| NORMAL | Electric trim works only to trim out column force (will not trim in same direction as column push) |
| OVERRIDE | Inhibits column-force-sensing cutout — allows trim in any direction regardless of column |

> [!warning] Runaway stabiliser
> 1. Both CUTOUT switches → CUT OFF
> 2. Use manual trim wheel if electric still doesn't stop
> Column-actuated cutout stops trim opposing column — if runaway in same direction as column: use CUTOUT switches

---

## Stabiliser Alignment Tabs

Three alignment tabs on left side of fuselage — see [[Stabiliser Alignment Tabs]]:

| Tab | Shows | Equivalent stab trim |
|-----|-------|---------------------|
| Upper | Max leading edge UP (4.2° LE up = nose down) | 0 units |
| Middle | Neutral (0° LE up) | 4 units |
| Lower | Max leading edge DOWN (12.9° LE down = nose up) | 17 units |

Full travel = **17.1°**

---

## Related
- [[Stabiliser Alignment Tabs]]
- [[Mach Trim]]
- [[Speed Trim System]]
- [[Pilot Controls and Indications]]
