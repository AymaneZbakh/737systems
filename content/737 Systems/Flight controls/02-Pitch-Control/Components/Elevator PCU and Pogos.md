---
tags: [B737, pitch, PCU, pogos, component]
parent: "[[Pitch Control]]"
location: Tail section / pressure bulkhead area
---

# Elevator PCU & Pogos
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Two Elevator Power Control Units — Left powered by Hyd A, Right powered by Hyd B. Each PCU receives commands from the Input Torque Tube through input pogos (also called load limiters or bungees).

---

## PCU Architecture

| Component | Count | Detail |
|-----------|-------|--------|
| PCUs | 2 | Left = Hyd A / Right = Hyd B |
| Input pogos | Per PCU | Receive input from torque tube |
| Actuator | Per PCU | Drives elevator surface |

---

## Pogo (Load Limiter / Bungee) Function

- Allows PCU operation **even after a jam occurs downstream** of the pogo
- If a pogo gets jammed: approximately **14 kg additional force** required on control column to move elevator to commanded position
- Pogo isolates the jam to prevent it from blocking the rest of the system

---

## Manual Reversion — Pitch

> [!note]
> With no hydraulic pressure:
> 1. Column must be displaced > **1°** (dead band)
> 2. Input cranks hit **mechanical stops**
> 3. PCU housing moves → elevator surface moves
> 4. Higher forces required (friction + aero loads)
> 5. **Elevator balance panels** move opposite to deflection to reduce forces needed

---

## A/P Input

- A/P mechanically moves the Input Torque Tube via the **A/P Actuator Input Crank**
- See [[AP Actuator Input Crank]]

---

## Related
- [[Elevators]]
- [[Elevator Aft Control Quadrant]]
- [[AP Actuator Input Crank]]
