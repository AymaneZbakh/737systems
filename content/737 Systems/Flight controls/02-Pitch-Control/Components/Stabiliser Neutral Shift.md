---
tags: [B737, pitch, neutral-shift, stabiliser, FCC, Mach-trim, component]
parent: "[[Pitch Control]]"
---

# Stabiliser Controlled Neutral Shift
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Flight Control Computers and Elevator Neutral Shift Rods change the neutral position of the elevator depending on stabiliser trim setting. Inputs are transferred through the Mach Trim Actuator.

---

## Function by Stab Trim Setting

| Stab Trim | Neutral Shift Direction | Degree | Reason |
|-----------|------------------------|--------|--------|
| 0 to 10.5 units | **Downrig** (elevator neutral shifted ~4° down) | ~4° | Reduces pitch force during initial climbout |
| 10.5 to 17 units | Gradually changes to **Uprig** | Variable | Decreases AOA of stabiliser; reduces risk of stabiliser buffet with ice on tailplane; decreases stab setting required for forward CG landing |

---

## Downrig Detail (0–10.5 units)

> [!info]
> With stab trim at 0–10.5 units (normal cruise/climb):
> - Elevator neutral is shifted approximately **4° down**
> - Reduces the pitch force required during initial climbout
> - Pilot perceives elevator as more effective nose-up

## Uprig Detail (10.5–17 units)

> [!info]
> With stab trim at 10.5–17 units (forward CG landing configuration):
> - Neutral shifts to uprig (nose-up)
> - Decreases AOA of stabiliser → reduces stabiliser buffet risk with tailplane icing
> - Lower stabiliser setting needed to maintain pitch during approach

---

## Mechanism

- Elevator Neutral Shift Rods connect FCC output to the elevator system
- Inputs transferred through the **Mach Trim Actuator**

---

## Related
- [[Mach Trim]]
- [[Stabilizer and Trim]]
- [[Stabiliser Alignment Tabs]]
