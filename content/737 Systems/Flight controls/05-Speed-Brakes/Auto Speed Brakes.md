---
tags: [B737, speed-brakes, auto, landing, RTO, Auto-Speedbrake-Module]
parent: "[[Speed Brakes]]"
---

# Auto Speed Brakes (Landing & RTO)
🔗 [[Speed Brakes|← Speed Brakes]]

> [!abstract]
> The Auto Speedbrake Module controls automatic speedbrake deployment during landing and RTO via the auto speedbrake actuator. Two deployment modes depending on lever position (ARM or DOWN detent).

---

## Auto Deployment — Lever in ARM Detent

All conditions must be met:

| Condition | Value |
|-----------|-------|
| Speed brake lever | ARMED |
| Radio altitude | < 10 ft |
| Main gear strut | Compressed (R strut compression also enables ground spoilers) |
| Both thrust levers | Retarded to IDLE |
| Main gear spin-up | > 60 kt **OR** main landing gear on ground |

→ **Auto speedbrake actuator moves lever to UP**
→ All flight spoilers deploy
→ R MLG strut compression → Ground Spoiler Interlock Valve opens → Ground spoilers deploy

---

## Auto Deployment — Lever in DOWN Detent

| Condition | Value |
|-----------|-------|
| Main gear spin-up | > 60 kt |
| Both thrust levers | Retarded to IDLE |
| Reverse thrust | Selected |

→ Spoilers deploy (flight spoilers via auto speedbrake actuator)

---

## Auto Stow

> [!info]
> When on the ground, the Auto Speedbrake Module moves the speed brake lever to **DOWN** when:
> - Either thrust lever is **advanced** (go-around initiated after touchdown, or RTO throttle advance)
> - Spoilers retract automatically

---

## SPD BRK DO NOT ARM Light (Amber)

> [!warning]
> Illuminates when:
> - Wheels < 60 kt upon landing, **AND**
> - Speed brake lever is **not** in DOWN position
>
> Indicates an abnormal auto-speedbrake condition. Do not arm system. Refer to QRH.

## SPEED BRAKE ARMED Light (Green)

> [!check]
> Speed brake lever in ARMED position — auto deployment system ready.

---

## Related
- [[Auto Speedbrake Module]]
- [[Ground Spoiler Interlock Valve]]
- [[Speed Brake Lever]]
- [[Flight controls/Quick-Reference/Warning Lights]]
