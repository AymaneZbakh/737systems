---
tags:
  - B737
  - flaps
  - trailing-edge
  - TE
  - PDU
  - torque-tubes
  - flap-control-unit
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# TE Flaps (Trailing Edge)
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> Double-slotted trailing edge flaps — inboard and outboard of each engine. Powered by Hyd B via a hydraulic/electric PDU. Mechanically driven via torque tubes and flap transmissions. 9 selectable positions.

---

## Effect by Position

| Positions | Effect |
|-----------|--------|
| 1° – 15° | Increased lift only |
| 15° – 40° | Increased lift **and** drag |

---

## Normal Drive System

```
FLAP lever → cables → Summing Lever (Flap Control Unit)
  → Hyd B via priority valve (LE devices get priority)
  → Flow limiter (controls TE flap speed)
  → Flap PDU (hydraulic motor + electric motor)
  → Torque Tubes (4 per side, 2 per TE flap)
  → TE Flap Transmissions (2 per flap)
  → TE Flap surface

Follow-up cables give opposing pressure to summing lever → stops drive at commanded position
```

> [!note] Electrically controlled, hydraulically operated
> During **normal operation**: mechanically controlled (FLAP lever) and hydraulically operated (Hyd B).
> During **alternate operation**: electrically controlled and electrically operated (electric motor in PDU).

---

## Priority Valve

- Hyd B pressure goes through a **priority valve** in the Flap Control Unit
- LE devices receive hydraulic priority **over** TE flaps when Hyd B pressure is low (below 2,400 psi)
- A **flow limiter** limits the speed of TE flap movement

---

## Flap Lever Gates

| Gate | Position | Purpose |
|------|----------|---------|
| 15° gate | Normal G/A setting | Prevents inadvertent selection beyond go-around flap |
| 1° gate | Single-engine G/A setting | Prevents inadvertent selection beyond single-engine go-around |

---

## Normal Landing Positions

| Flap Setting | Use |
|---|---|
| Flaps 15 | Performance-limited airports (approach climb constraint) |
| Flaps 30 | Standard short-field or normal |
| Flaps 40 | Standard normal landing |

---

## Limits

- **Maximum altitude**: 20,000 ft
- Overspeed protection: see [[Flap Load Relief]]

---

## Related
- [[Flap Load Relief]]
- [[FSEU Protection]]
- [[Alternate Extension]]
