---
tags:
  - B737
  - flaps
  - autoslats
  - stall
  - PTU
  - SMYD
  - protection
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# Autoslats
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> Extends LE slats from extended to full extended position when approaching stall — before stickshaker activation. Enhances stall characteristics. Normally powered by Hyd B; backup via PTU from Hyd A EDP.

---

## Activation Conditions

| Aircraft | TE Flap Range | Autoslats Active |
|----------|--------------|-----------------|
| SFP (737-800) | 1° – 25° | ✅ |
| NON-SFP | 1° – 5° | ✅ |

- When approaching **stall** within these flap settings: autoslats extend slats to **FULL EXT**
- Activates **prior to stickshaker**

---

## Hydraulic Power

| Source | Condition |
|--------|-----------|
| **Hyd B** | Normal |
| **PTU → Hyd B** (via Hyd A Engine Driven Pump) | Backup when loss of pressure sensed from higher-volume Hyd B EDP (e.g. engine failure) |

> [!info]
> The PTU (Power Transfer Unit) senses when Hyd B volume/pressure drops (e.g. from engine failure on the Hyd B engine) and transfers Hyd A pressure to maintain autoslat function.

---

## Stall Sequence — Autoslat Role

| Step | System | Action |
|------|--------|--------|
| 1 | STS | Trims stab nose-down |
| 2 | SMYD / Yaw Damper | Reduces YD rudder movement |
| 3 | EFS | Increases column forces ~4× |
| **4** | **Autoslats** | **Extend LE slats: EXT → FULL EXT** |
| 5 | Stickshaker | Activates |

---

## After Activation

- Slats return to **extended** (not full extended) position when AOA is reduced below autoslat activation threshold

---

## AUTO SLAT FAIL Light (Amber)

> [!warning]
> On recall = single **SMYD (Stall Management Yaw Damper) computer failure**.
> Stall margins may be reduced at affected flap configurations.
> Stickshaker remains operative.

---

## Related
- [[LE Devices]]
- [[Stall Identification (EFS)]]
- [[Speed Trim System]]
- [[Flight controls/Quick-Reference/Warning Lights]]
