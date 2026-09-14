---
tags: [B737MAX, MAX-8, flight-controls, MCAS, STS, FCC, stabilizer, trim]
system: Flight Controls
---

# 🎮 MAX-8 Flight Controls
🔗 [[Home - MAX Differences]] | [[APU|← APU]] | [[Spoilers|Next: Spoilers →]]

> [!abstract] Overview
> Key flight control differences on the MAX include new stab trim cutout switch naming, a new software column cutout function, and the addition of MCAS (Maneuvering Characteristics Augmentation System). MCAS is the most significant new system — it provides pitch stability augmentation due to the different engine position and nacelle shape of the LEAP engines.

---

## Stabilizer Trim Cutout Switches

> [!note] Renamed switches — same function
> The 737 MAX has new stab trim cutout switches named **PRI** and **B/U**. These replace "MAIN ELEC" and "AUTO PILOT" on 737 NG.
> QRH actions for stab trim cutout switches remain unchanged ("Runaway Stabiliser" and "Stabiliser Trim Inoperative").

| Switch | MAX Name | NG Name | Effect when CUT OUT |
|--------|----------|---------|---------------------|
| Primary | **PRI** | MAIN ELEC | Deactivates main electric, autopilot, STS and MCAS trim |
| Backup | **B/U** | AUTO PILOT | Deactivates main electric, autopilot, STS and MCAS trim |

- Both NG and MAX have **control column actuated stabiliser cutout switches**
- These cutout switches stop main electric, autopilot, and STS trim when control column is moved in the opposite direction

---

## Software Column and Control Column Stabiliser Cutout (MAX New)

> [!info] MAX-only feature
> MAX has a **backup software column cutout** function which inhibits autopilot and STS trim commands when the control column is moved in the opposite direction to the trim command.

Software column and control column stabiliser cutout switches:
- **Do NOT** stop MCAS nose down trim if control column moves aft
- **Stop** MCAS nose up trim if control column moves forward

---

## Maneuvering Characteristics Augmentation System (MCAS)

> [!warning] MCAS — Critical system to understand
> Due to the different engine position (more forward) and the nacelle shape of LEAP engines, the manoeuvring characteristics of the 737 MAX have slightly changed, and the control column forces do not naturally increase with increasing angle of attack. MCAS was installed to restore compliance with certification standards.

### MCAS vs STS

| System | Function | Speed |
|--------|----------|-------|
| **STS** | Speed stability augmentation | Speed-based |
| **MCAS** | Pitch stability augmentation | AOA/Mach-based |

- MCAS trim is noticeably **faster** than STS trim (equal to STS flaps extended speed)
- MCAS has **priority over STS** — high AOA Mode

---

### MCAS Activation Conditions

MCAS automatically trims nose down when **all** of the following:

| Condition | Value |
|-----------|-------|
| Angle of Attack | High (sensed by both AOA sensors) |
| Mach | < M0.84 |
| Time after take-off | > 10 seconds |
| Autopilot | Disengaged |
| Flaps | Up |

---

### MCAS Command Logic

- MCAS is a function of FCC and takes AOA data from **both AOA vanes**
- Small differences between AOA vanes are filtered to provide single corrected AOA value
- FCC software compares inputs from two sensors to detect a failed AOA sensor
- MCAS commands are based on **Angle of Attack (AOA)** and **Mach Number**
- Commands added **incrementally** (up to the maximum command limit)
- When AOA decreases below threshold → MCAS **reverses its commands**
- Revised flight control laws permit only **one activation** of MCAS per sensed high AOA event
  - Subsequent activation possible only after aeroplane returns to low AOA state below the threshold

### MCAS Command Limits

> [!warning] Maximum command limits
> FCC **limits the magnitude** of any MCAS commands to move the horizontal stabiliser. The final horizontal stabiliser position (after MCAS activation) will preserve the flight crew's ability to control pitch using elevator only.

The maximum nose-down MCAS command is derived from the **trim setting just before MCAS activation (snapshot position)**:

| Condition | Max Nose-Down Command from Snapshot |
|-----------|-------------------------------------|
| Low Mach | **2.5 units** |
| High Mach | **0.65 units** |

**When flaps retracted UP:** MCAS only activates if AOA transitions from below threshold to above threshold (prevents scenarios where both AOA vanes are erroneously high).

---

### MCAS and Maximum Command Limit

When the maximum command limit is reached:
- **SPEED TRIM FAIL** light illuminates
- STS and MCAS are **inoperative until landing**

The maximum command limit logic is **reset** if the limit has NOT been reached:
- Within **5 minutes** after MCAS activation (manual flight)
- Within **1 minute** after A/P engagement (following MCAS activation)

Additional behaviours:
- Trimming nose up while MCAS is active will **pause** the automatic MCAS nose down trim
- MCAS can also be disabled by switching the **Stabilizer Trim Cutout Switches to CUTOUT**

---

### AOA Sensor Disagreement

If the difference between the AOA sensor inputs is **5.5° or more**:
- FCC will **disable STS and MCAS** for the remainder of the flight
- **SPEED TRIM FAIL** light illuminates
- Note: **AOA DISAGREE** alert illuminates when difference is more than **10 degrees**

---

## FCC Cross Trim Monitor

> [!info] Protection against stabiliser runaway
> Provides another layer of protection against stabiliser runaway due to erroneous FCC trim commands.

- When erroneous trim commands detected → trim commands from erroneous FCC are **inhibited**
- Other FCC **takes over**
- **SPEED TRIM FAIL** light may illuminate (either on recall or with Master Caution)
- **STAB OUT OF TRIM** illuminates after landing when below 30 knots
- A/P may disengage → may not be possible to re-engage A/P on the side of the failed FCC

---

## Related
- [[Spoilers]] — FBW spoiler system
- [[AOA Sensors]] — dual AOA input
- [[Flight controls/Quick-Reference/Warning Lights]]
- [[Fuel/Quick-Reference/Key Numbers]]
