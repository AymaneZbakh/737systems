---
tags: [B737, yaw, feel-centering, rudder-trim, component]
parent: "[[Yaw Control]]"
---

# Rudder Feel & Centering Unit
🔗 [[Yaw Control|← Yaw Control]]

> [!abstract]
> Provides artificial feel forces to the rudder pedals and defines the aerodynamic neutral position of the rudder. The Rudder Trim Actuator repositions the unit to apply trim.

---

## Function

- Provides centering force to rudder pedals (returns pedals to neutral when released)
- Feel force simulates aerodynamic feedback
- Neutral position can be **redefined by the Rudder Trim Actuator**

## Trim Actuator

- Electrically positions the Feel & Centering Unit
- Powered by **XFR Bus #2**
- When repositioned: rudder pedals physically displace to reflect new neutral
- Yaw damper inputs feed into the PCU independent of the feel & centering unit

---

## Related
- [[Rudder Trim]]
- [[Rudder (RSEP)]]
