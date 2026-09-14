---
tags: [B737MAX, MAX-8, landing-gear, nose-strut, autobrake, PSEU]
system: Landing Gear
---

# 🛬 MAX-8 Landing Gear
🔗 [[Home - MAX Differences]] | [[MAX Differences/07-Flaps-Slats/Flaps and Slats|← Flaps & Slats]] | [[Fuel|Next: Fuel →]]

> [!abstract] Overview
> The most visible landing gear change is the nose wheel strut extended by 20.3 cm to maintain ground clearance for the larger LEAP-1B engines. The landing gear lever and control panel have also been redesigned.

---

## Nose Landing Gear

| Feature | Detail |
|---------|--------|
| Nose wheel strut extension | **+20.3 cm (8")** vs NG |
| Reason | Ground clearance for LEAP-1B engines |
| Rudder pedal nose wheel steering | **6°** (NG: 7°) |
| LAM interaction | LAM feature of FBW spoilers ensures nose landing gear contact margins on landing remain similar to NG |

---

## Landing Gear Lever

> [!note] No OFF position
> The most noticeable difference in the flight deck is the new landing gear lever.

| Feature | NG | MAX |
|---------|----|-----|
| OFF position | Present | **No OFF position** |
| Lever → LG Selector Valve connection | Mechanical | **No mechanical connection** |
| Retract hydraulic pressure removal | Manual | **PSEU automatically removes retract HYD pressure** 10 seconds after gear is UP and locked |

---

## Other Landing Gear Component Relocations

Following components relocated **between the CDUs** (where lower DU used to be on NG):
- Autobrake selector
- **AUTOBRAKE DISARM** light
- **ANTISKID INOP** light
- Brake Accumulator Pressure Indicator

Additional changes:
- **Nose Wheel Steering switch** relocated next to the landing gear lever
- **Landing Gear Lever Lock Override** is now a **button** (instead of a trigger on NG)

---

## Main Wheel Well Fire Detection

- Now in a **dual loop configuration** (NG: single loop)

---

## (Option) TIRE PRESSURE

The TIRE PRESSURE light will illuminate when:
- Main or nose wheel tire pressure falls below **100 psi**
- More than **25% pressure difference** between 2 wheel tires on the same main landing gear
- More than **12% pressure difference** between nose wheel tires

Tire pressure will turn amber on the MFD SYS page.

---

## (Option) New Autobrake Setting

This option reprogrammes target deceleration for AB 1, 2, and 3:

| Autobrake | New Target Deceleration | Notes |
|-----------|------------------------|-------|
| AB 1 | Gets target decel of AB 2 (5 ft/sec²) | |
| AB 2 | Gets target decel of AB 3 (7.2 ft/sec²) | |
| AB 3 | **9.5 ft/sec²** | AB MAX 14 ft/sec² unchanged |

---

## Related
- [[Spoilers]] — LAM and landing attitude
- [[Fuel/Quick-Reference/Key Numbers]]
- [[Flight controls/Quick-Reference/Warning Lights]]
