---
tags: [B737, roll, PCU, pogos, component]
parent: "[[Roll Control]]"
location: Main wheel well
---

# Aileron PCU & Pogos
🔗 [[Roll Control|← Roll Control]] | [[Ailerons|← Ailerons]]

> [!abstract]
> Two Aileron Power Control Units located in the main wheel well. Each PCU connected to the Aileron Input Shaft by 4 pogos (2 per PCU). Powered by Hyd A (right PCU) and Hyd B (left PCU).

---

## PCU Architecture

| Component | Count | Function |
|-----------|-------|---------|
| PCUs | 2 | Convert hydraulic pressure to aileron surface movement |
| Pogos | 4 (2 per PCU) | Connect PCU to Aileron Input Shaft; isolate jams |
| Input cranks | 2 per PCU | Receive pogo input; command PCU actuator |

---

## Pogo Function

- Each PCU connected to the [[Aileron Input Shaft|Aileron Input Shaft]] by **2 pogos**
- Pogos can **extend and retract** when a jam occurs on the PCU side
- Extension/retraction **isolates the jam** and allows freedom of movement to the rest of the system
- Pogos move input cranks inside the PCU
- Input cranks command the PCU actuator to move [[Aileron Body Quadrants|Aileron Body Quadrants]]

---

## Manual Reversion via PCU

> [!note]
> When **no hydraulic pressure** is supplied to the PCUs:
> 1. Control wheel must be turned > **3°** (dead band)
> 2. Input cranks inside PCU hit **mechanical stops**
> 3. Mechanical stops start moving the **PCU housing**
> 4. PCU housing movement drives Aileron Body Quadrants to commanded position
>
> Higher control forces required due to friction and aerodynamic loads.

---

## Related
- [[Aileron Input Shaft]]
- [[Aileron Body Quadrants]]
- [[Ailerons]]
