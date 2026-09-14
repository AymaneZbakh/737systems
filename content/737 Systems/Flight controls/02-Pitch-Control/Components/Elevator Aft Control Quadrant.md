---
tags: [B737, pitch, aft-quadrant, component, torque-tube]
parent: "[[Pitch Control]]"
---

# Elevator Aft Control Quadrant
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Receives commands from the FWD Control Quadrant via Elevator Control Cables (which pass through the pressure bulkhead). Supplies input to the Input Torque Tube which commands the PCUs.

---

## Signal Chain

```
FWD Control Quadrant (L or R)
  → Elevator Control Cables (through pressure bulkhead)
  → Elevator AFT Control Quadrant (L or R)
  → Input Torque Tube
  → Elevator PCU
```

---

## Notes

- Control cables pass through the **pressure bulkhead** (pressurised to unpressurised zone)
- Left and right AFT quadrants are mechanically independent — jam in one does not block the other (breakout mechanism)

---

## Related
- [[Elevators]]
- [[Elevator PCU and Pogos]]
