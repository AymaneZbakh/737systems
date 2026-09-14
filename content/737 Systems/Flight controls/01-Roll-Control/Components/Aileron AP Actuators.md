---
tags: [B737, roll, autopilot, actuator, component]
parent: "[[Roll Control]]"
---

# Aileron A/P Actuators
🔗 [[Roll Control|← Roll Control]]

> [!abstract]
> Autopilot actuators control ailerons and spoilers through the aileron input shaft. The A/P actuator is connected to the Aileron Input Shaft and commands roll via the same mechanical path as the CPT control wheel.

---

## A/P Roll Control Path

```
A/P Actuator → Aileron Input Shaft → Feel & Centering Unit → Aileron PCUs → Ailerons
                                   ↓
                             Spoiler Mixer → Flight Spoilers
```

> [!warning] Aileron trim with A/P engaged
> The A/P actuator overpowers any aileron trim input to maintain the commanded bank angle.
> On disconnect, the stored out-of-trim results in an **abrupt aileron swing**.
> **Aileron trim with A/P engaged is prohibited.**

---

## Related
- [[Aileron Trim]]
- [[Aileron Input Shaft]]
- [[Aileron Feel and Centering Unit]]
