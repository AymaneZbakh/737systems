---
tags: [B737MAX, MAX-8, air-systems, bleed, IASC, packs]
system: Air Systems
---

# 🌬 MAX-8 Air Systems
🔗 [[Home - MAX Differences]] | [[Anti-Ice|Next: Anti-Ice →]]

> [!abstract] Overview
> The 737 MAX transitions from a **pneumatic** (NG) to a **digitally controlled** air conditioning and pressurisation system. The overhead panels look almost identical to the NG, but the underlying systems are significantly different. The IASC (Integrated Air Systems Controller) digitally manages both bleed air and air conditioning.

---

## Key Changes vs NG

| Feature | NG | MAX-8 |
|---------|----|-------|
| Bleed air stages | 5th & 9th stage | **4th & 10th stage** |
| Single bleed source | Cannot supply both packs | **Can supply both packs in flight** |
| Fault detection | Manual identification | Auto-detecting and auto-isolating |
| System control | Pneumatic | **Digital (IASC)** |
| RAM AIR FULL OPEN lights | Present | **Removed** |
| Air Conditioning control | Pneumatic | **Digitally controlled** |
| Fault storage | Local | Centralised maintenance system |

> [!tip] Digital advantage
> Digital control improves engine efficiency, decreases mechanical complexity, and allows all system faults to be stored in centralised maintenance systems. Duct pressure splits and in-flight discrepancies are easier to identify.

---

## IASC — Integrated Air Systems Controller

> [!note] Dual IASCs — L and R
> Two identical IASCs (Left and Right) digitally control their respective engine bleed and air conditioning systems.

Each IASC has **two independent sub-systems**:

| Sub-system | Acronym | Function |
|-----------|---------|---------|
| Air Supply Controller | **ASC** | Controls engine bleed air system |
| Pack Flow and Temperature Controller | **PFTC** | Controls air conditioning system |

- Each ASC and PFTC has a **backup control** as a redundancy
- IASC receives data from various sensors and adjusts the HPSOV, PRSOV, and Fan Air Modulating Valve based on bleed air demand
- IASC performs **Post Flight Built-In Test (PFBIT)** of PRSOV after landing → causes duct pressure to split after landing

---

## Pressure Regulator Shutoff Valve (PRSOV)

- Pneumatically actuated
- **Electrically controlled** when HPSOV is closed → controls manifold to 45 ±5 psi
- **Pneumatically regulated** when HPSOV is open → regulates manifold to 60 psi ±11 psi
- IASC uses data from the **Manifold Pressure Sensor (PM)** to control the PRSOV

---

## High-Pressure Shutoff Valve (HPSOV)

- Regulates bleed air supply from the **10th High Pressure Compressor (HPC)** stage
- Maintains sufficient bleed air supply at low thrust settings (same function as High Stage Valve on NG)
- IASC uses the **Intermediate Manifold Pressure Sensor (PI)** to control HPSOV electrically
  - Adjusts HPSOV to maintain PI pressure **30 to 65 psi**
- Controlled by a **torque motor**
- Mechanical back-up when IASC is not controlling:
  - Engine running → self-regulates to **55 psi**
  - Engine shut-down → **spring-load closes**

---

## Duct Vent Valve

- Provides over-pressure protection of ducts upstream of the PRSOV when PRSOV is closed with engine at high thrust (no engine bleed take-off)

---

## BLEED Light

> [!warning] BLEED Light — replaces BLEED TRIP OFF
> Single BLEED light replaces the NG BLEED TRIP OFF light.

**Single light** illuminates for:
- Over-pressure (170 psi for 5 sec at PI)
- Over-temperature (254°C/490°F for 20s at TM)
- Under-pressure
- Fault in bleed air system (may not be resettable)

**Both lights** illuminate when:
- In flight with both bleed air switches OFF 45 seconds after flaps retracted after take-off or go-around
- **Lights will NOT illuminate** if both engine bleed air switches placed to OFF 10 minutes after flaps retracted (no engine bleed landing) — timer resets when flaps are extended

---

## PACK Light

**Single PACK light** illuminates for:
- Overheat
- PACK Control failure (both primary and standby)
- PACK Control Valve fails to open when commanded on
- Note: Failure of either primary or standby PACK control → **MAINT** light on landing (PACK does not illuminate on recall)

**Both PACK lights** illuminate when:
- In flight with both PACK switches OFF 45 seconds after flaps retracted after take-off

---

## EQUIP SMOKE Light (New on MAX)

> [!info] New indication — not on NG
> When smoke detected in equipment cooling system:
> - PACKs automatically switch to **high flow**
> - Equipment Cooling Supply fans switch OFF for ~5 minutes (OFF light inhibited)
> - Recirculation fans turn OFF
> - Overboard Exhaust Valve opens to **Smoke Removal** position
> - Light extinguishes approx. 30 seconds after smoke is no longer detected

---

## Related
- [[Anti-Ice]] — uses bleed air
- [[Engines]] — LEAP-1B bleed air characteristics
- [[Flight controls/Quick-Reference/Warning Lights]]
