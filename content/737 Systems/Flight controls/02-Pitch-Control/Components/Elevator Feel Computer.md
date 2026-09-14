---
tags: [B737, pitch, feel-computer, component]
parent: "[[Pitch Control]]"
location: Tail section (unpressurised zone)
---

# Elevator Feel Computer
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Generates hydraulic feel pressure for the Elevator Feel & Centering Unit based on airspeed (pitot/static) and stabiliser position. Located in the unpressurised tail section.

---

## Inputs

| Input | Source | Port |
|-------|--------|------|
| Pitot pressure (airspeed) | Pitot probe on vertical stabiliser | Pitot port |
| Static pressure | Static source on vertical stabiliser | Static port |
| Stabiliser position | Stabiliser Input Rod to Feel Computer | Mechanical input |
| Hydraulic supply | Hyd A or B (whichever is higher) | Hydraulic input |

---

## Output

- Controlled hydraulic pressure to **Elevator Feel & Centering Unit**
- Output pressure increases with:
  - Higher airspeed
  - More nose-up stabiliser setting
- Normal output: variable
- EFS activated output: **~850 psi** (Hyd A)

---

## Location

Located in the **unpressurised zone** of the tail section, accessible from the exterior.

---

## FEEL DIFF PRESS (Amber)

> [!warning]
> One hydraulic system or one pitot probe has failed.
> Feel computer operating on single source → possible abnormal column forces.

---

## Related
- [[Elevator Feel System]]
- [[Stall Identification (EFS)]]
