---
tags: [B737, pitch, mach-trim, FCNSE, FCC]
parent: "[[Pitch Control]]"
---

# Mach Trim
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Prevents Mach tuck above Mach 0.615 by commanding a nose-up elevator input via the Mach Trim Actuator. Also active during takeoff to increase pitch-up authority in case of engine failure (FCNSE region).

---

## Normal Operation

| Parameter | Value |
|-----------|-------|
| Activation | > Mach 0.615 |
| Signal source | ADIRU L/R → FCC → Mach Trim Actuator |
| Effect | Repositions elevator feel & centering unit nose-up as Mach increases |
| Purpose | Counteracts nose-down Mach tuck tendency |

```
ADIRU L/R → FCC → Mach Trim Actuator → elevator neutral shift
```

---

## Takeoff — FCNSE Region

> [!info] FCC Controlled Neutral Shift Enable (FCNSE)
> The Mach Trim Actuator also **increases elevator movement during takeoff** when:
> - Flaps are **NOT** up, AND
> - N1 is more than **20%**
>
> This provides **higher pitch-up authority** in case of engine failure during takeoff.
> This region is called the **FCNSE (FCC Controlled Neutral Shift Enable) region**.

---

## MACH TRIM FAIL Light (Amber)

> [!warning]
> On recall = single Flight Control Computer (FCC) failure.
> Limit airspeed to avoid degraded Mach tuck compensation.
> Refer to QRH for applicable speed restrictions.

---

## Related
- [[Speed Trim System]]
- [[Elevator Feel System]]
- [[Key Speeds and Limits]]
- [[Flight controls/Quick-Reference/Warning Lights]]
