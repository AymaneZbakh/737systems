---
tags: [B737MAX, MAX-8, spoilers, FBW, SCE, GSCM, LAM, MLA, EDS, EJLA]
system: Spoilers
---

# 🛩 MAX-8 Spoilers — Fly-By-Wire
🔗 [[Home - MAX Differences]] | [[Flight Controls|← Flight Controls]] | [[MAX Differences/07-Flaps-Slats/Flaps and Slats|Next: Flaps & Slats →]]

> [!abstract] Overview
> The spoilers on the 737 MAX are **fly-by-wire (FBW)**. This reduces weight, improves stopping distance, and introduces new features not possible with mechanical solutions. The mechanical spoiler mixer and ground spoiler control valve are replaced by electronic units.

---

## NG vs MAX Spoiler Architecture

| Component | NG | MAX |
|-----------|-----|-----|
| Spoiler command | Mechanical mixer | **Spoiler Control Electronics (SCE) Unit** |
| Ground spoiler valve | Mechanical control valve | **Ground Spoiler Control Module (GSCM)** |
| System type | Mechanical | **Fly-By-Wire** |
| Speedbrakes with F40 | Allowed | **Should NOT be extended** |

---

## Spoiler Control Electronics (SCE) Unit

- Gathers data from position sensors in the speedbrake lever, F/O's control wheel, and from other aeroplane systems
- Controls spoilers by sending electrical control signal to flight spoiler **Power Control Units (PCUs)**
- Each flight spoiler has its own PCU
- PCUs translate the control signal and send hydraulic pressure to their respective flight spoiler actuators

### SPOILERS Light

> [!warning] SPOILERS light
> Illuminates when there is a fault in the spoiler system detected by the SCE Unit.

---

## Ground Spoiler Control Module (GSCM)

- Controls the **ground spoilers** by sending electrical control signal to ground spoiler PCUs
- Replaces the function of the mechanical ground spoiler control valve
- Gathers **speedbrake lever position** together with **air/ground data**
- On the ground with GSCM: commands ground spoilers to extend when speedbrake lever is beyond flight detent
- There is still a mechanical **ground spoiler interlock valve** which will open when **both** main landing gear struts are compressed (737 NG only right main landing gear strut) to allow HYD A to the ground spoiler PCUs

---

## New Spoiler Features (FBW only)

### Landing Attitude Modifier (LAM)

> [!note] Flaps 15 to 30 — controls nose attitude on landing
> When thrust levers are near idle, LAM extends the spoilers to catch and maintain the glide path similar to the NG.

| Flap Setting | LAM Behaviour |
|-------------|---------------|
| Flaps **15 to 30** | LAM extends spoilers to catch/maintain glide path. Speedbrake lever does not move. |
| Flaps **30 to 40** | Flight spoilers **deploy symmetrically** to increase pitch angle and keep similar nose landing gear contact margins to NG (MAX nose wheel strut is 8" longer). Speedbrake lever does not move. Variable deflection with speed: VREF+10 → spoilers begin to deploy; VREF+20 → maximum deflection |

---

### Elevator Jam Landing Assist (EJLA)

> [!warning] For jammed or restricted pitch control
> System designed for jammed or restricted pitch control (jammed elevator).

- EJLA uses spoilers to adjust pitch attitude for approach and landing
- When activated: flight spoilers extend to a **neutral position (Direct Lift Control)**
- EJLA converts forces applied on the control column into spoiler commands:
  - **Push** = flight spoilers extend from neutral position
  - **Pull** = flight spoilers retract from neutral position
- Dedicated **Elevator Jam Landing Assist panel** located on aft overhead

**Activation conditions:**
- EJLA switch is ON
- Flaps are 1 or greater
- Autopilot is disengaged

**ASSIST ON** light indicates EJLA is active.

---

### Emergency Descent Speedbrakes (EDS)

> [!warning] Increases descent rate during emergency descent
> EDS extends spoilers **slightly beyond maximum flight deflection** to increase drag.

**EDS activates when ALL of:**
- **CABIN ALTITUDE** warning is active
- Altitude above **30,000 ft**
- Speedbrake in flight detent

EDS operates as long as the CABIN ALTITUDE warning is active OR the speedbrake lever is not stowed.

---

### Manoeuvre Load Alleviation (MLA)

> [!info] Structural protection at high gross weights
> MLA partially retracts the spoilers to reduce the wing and aft fuselage bending loads during high gross weights at normal load factors.

- Speedbrake lever **does not move** when MLA is active
- System activates for the load factors:
  - Above **1.3g**
  - Below **0.3g**
- When MLA is no longer active: spoilers return to commanded speedbrake lever position

---

## SPEED BRAKE EXTENDED Light — Additional Conditions (MAX only)

> [!note] MAX illuminates in two more cases vs NG
> On 737 MAX, the SPEED BRAKE EXTENDED light will also illuminate when:
> - **Go-around thrust** is set for **3 seconds**
> - Thrust is **above idle for 15 seconds**

---

## Performance Advantages of FBW Spoilers

| Advantage | Notes |
|-----------|-------|
| Enhanced roll control | Improved spoiler authority |
| Lower maintenance cost | Fewer mechanical components |
| Reduced weight | vs mechanical system |
| Reduced stopping distance | Full 60° spoiler deflection |

---

## Related
- [[Flight Controls]] — MCAS and stab trim
- [[MAX Differences/07-Flaps-Slats/Flaps and Slats]] — flap settings interact with LAM
- [[Flight controls/Quick-Reference/Warning Lights]]
