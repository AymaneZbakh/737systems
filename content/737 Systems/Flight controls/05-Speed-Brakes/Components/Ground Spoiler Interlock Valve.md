---
tags: [B737, speed-brakes, interlock-valve, ground-spoiler, component]
parent: "[[Speed Brakes]]"
location: Main wheel well area
---

# Ground Spoiler Interlock Valve
🔗 [[Speed Brakes|← Speed Brakes]]

> [!abstract]
> Prevents ground spoilers from deploying in flight. The valve is CLOSED when in the air and opens ONLY when weight is on the Right Main Gear — allowing Hyd A pressure to flow to ground spoiler actuators.

---

## Valve Logic

| Aircraft State | Interlock Valve | Ground Spoilers |
|----------------|----------------|-----------------|
| In the air | **CLOSED** | Cannot deploy |
| Weight on Right MLG | **OPEN** | Can deploy (if Hyd A pressure available from Ground Spoiler Control Valve) |

---

## Air/Ground Signal — Push-Pull Cable

- The **[[Push-Pull Cable|Push-Pull Cable]]** connected to the **Right Main Gear** provides the air/ground command to the Interlock Valve
- When Right MLG strut compresses (weight on wheels): push-pull cable opens the Interlock Valve mechanically

---

## Fail-Safe Protection

> [!danger] Interlock valve fails OPEN after takeoff
> If the Ground Spoiler Interlock Valve fails open after takeoff:
> - The **landing gear lever locking solenoid** will keep the landing gear lever **locked in the DOWN position**
> - This prevents gear retraction with ground spoilers potentially active
> - Refer to QRH for Gear Will Not Retract procedure

---

## Full Deployment Path

```
Speedbrake lever > FLIGHT DETENT
  → Ground Spoiler Control Valve opens (Hyd A)
  → Hyd A flows to Ground Spoiler Interlock Valve
  → Push-Pull Cable: Right MLG compressed → Interlock Valve opens
  → Hyd A flows to Ground Spoiler Actuators
  → Ground spoilers deploy
```

---

## Related
- [[Ground Spoiler Control Valve]]
- [[Push-Pull Cable]]
- [[Auto Speed Brakes]]
