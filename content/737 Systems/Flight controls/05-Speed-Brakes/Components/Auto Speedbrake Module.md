---
tags: [B737, speed-brakes, auto-speedbrake-module, component]
parent: "[[Speed Brakes]]"
location: Wheel well / electronics bay
---

# Auto Speedbrake Module
🔗 [[Speed Brakes|← Speed Brakes]]

> [!abstract]
> Controls the automatic operation of the speedbrakes during landing and RTO through the auto speedbrake actuator. Monitors wheel spin-up, thrust lever position, radio altitude, and strut compression to determine when to deploy and stow.

---

## Module Inputs

| Input | Source |
|-------|--------|
| Main gear spin-up (> 60 kt) | Wheel speed sensors |
| Radio altitude | Radio altimeter (< 10 ft) |
| Thrust lever position | IDLE / Reverse thrust switches |
| Right MLG strut compression | WOW switch |
| Speedbrake lever position | Lever position sensor |

---

## Auto Deploy Logic

### Lever in ARM

Deploy when ALL:
- RA < 10 ft
- R strut compressed
- Both TLs at IDLE
- Spin-up > 60 kt OR MLG on ground

### Lever in DOWN

Deploy when ALL:
- Spin-up > 60 kt
- Both TLs at IDLE
- Reverse thrust selected

---

## Auto Stow Logic

- Either thrust lever **advanced** (go-around or RTO abort)
- → Module commands lever to **DOWN**
- → Spoilers retract

---

## SPD BRK DO NOT ARM (Amber)

> [!warning]
> Wheels < 60 kt on landing AND speed brake not in DOWN position.
> Abnormal condition — do not arm. Refer to QRH.

---

## Related
- [[Auto Speed Brakes]]
- [[Speed Brake Lever]]
- [[Ground Spoiler Interlock Valve]]
