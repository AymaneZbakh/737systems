---
tags: [B737, yaw, rudder, RSEP, load-limiter, PCU]
parent: "[[Yaw Control]]"
---

# Rudder (RSEP)
🔗 [[Yaw Control|← Yaw Control]]

> [!abstract]
> Single rudder surface with Rudder System Enhancement Program (RSEP). Main PCU has 2 independent input rods, control valves, and actuators — one per hydraulic system. Load limiter reduces authority above 137 kts.

---

## Main PCU Architecture

| Component | Count | Detail |
|-----------|-------|--------|
| Input rods | 2 | One per hydraulic system; each has individual jam override |
| Control valves | 2 | One per input rod |
| Actuators | 2 | One per hydraulic system (Hyd A / Hyd B) |

- Each pedal set mechanically connected by cables to the input levers of both main and standby rudder PCU
- Either input rod can independently operate the rudder

---

## Load Limiter

| Speed | Status |
|-------|--------|
| ≤ 132 kts | Full rudder authority |
| 132 – 137 kts | Transition zone |
| > 137 kts | Hyd A and B pressure in main PCU **reduced by ~25%** → reduced max travel |

> [!warning]
> Load limiter applies to **main PCU only**.
> Standby PCU retains full authority — use carefully at high speed.

---

## Rudder Pedals

- Provide nose gear steering up to **7°** on ground
- Rudder becomes aerodynamically effective at **40–60 kts**
- Maximum rudder travel: **29° L/R**
- Both FO and CPT pedal sets mechanically connected to same PCU inputs

---

## Jam Override

- Each input rod has its own **jam override mechanism**
- If one input rod jams, the other rod continues to operate its actuator independently
- No total loss of rudder from a single jam

---

## Related
- [[Standby Rudder and FFM]]
- [[Rudder Trim]]
- [[Key Speeds and Limits]]
- [[Hydraulic Power Sources]]
