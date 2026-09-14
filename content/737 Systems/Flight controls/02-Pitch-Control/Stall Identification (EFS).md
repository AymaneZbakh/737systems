---
tags: [B737, pitch, stall, EFS, SMYD, protection]
parent: "[[Pitch Control]]"
---

# Stall Identification & Control (EFS)
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Four systems work together — STS, Yaw Damper (SMYD), EFS Module, and Autoslats — to enhance stall identification and control. All receive commands from SMYD computers.

---

## Components & Their Role

| System | Role during stall approach |
|--------|---------------------------|
| **STS** | Continues to trim nose-down above stick-shaker AOA at idle thrust |
| **Yaw Damper (SMYD)** | Reduces yaw damper rudder movement at high AOA |
| **EFS Module** | Increases HYD A pressure to 850 psi → column force ~4× normal |
| **Autoslats** | Extends LE slats to full extended position |

---

## EFS Module Detail

- Increases **Hyd A pressure to 850 psi** to the Elevator Feel & Centering Unit
- Increases control column force to approximately **4× normal feel pressure**
- Designed so pilots **cannot easily overpower** STS nose-down trimming during stall
- Activates when AOA is **2.7°–10.2° above stick-shaker AOA**

### EFS Inhibited When (ANY of the following)

| Condition | Status |
|-----------|--------|
| On ground | Inhibited |
| Radio altitude < 100 ft | Inhibited |
| A/P engaged | Inhibited |

> [!warning]
> If EFS was activated **before** the inhibit criteria is met, it **stays active**.

---

## Stall Sequence (approaching stall)

1. AOA increases
2. **STS** trims stab nose-down
3. **SMYD** reduces yaw damper inputs
4. **EFS** activates → column forces increase to 4× normal (AOA 2.7°–10.2° above stick shaker)
5. **Autoslats** extend to full extended position
6. **Stick shaker** activates

---

## Related
- [[Elevator Feel System]]
- [[Speed Trim System]]
- [[Autoslats]]
- [[Yaw Damper]]
- [[Flight controls/Quick-Reference/Warning Lights]]
