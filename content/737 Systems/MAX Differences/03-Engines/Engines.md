---
tags: [B737MAX, MAX-8, LEAP-1B, engines, CFM, EEC, BRM, EOS, TCMA]
system: Engines
---

# ⚙️ MAX-8 Engines — LEAP-1B
🔗 [[Home - MAX Differences]] | [[Anti-Ice|← Anti-Ice]] | [[APU|Next: APU →]]

> [!abstract] Overview
> The **CFM LEAP-1B** is the major improvement on the 737 MAX. It replaces the CFM56-7 and provides approximately **15% improvement in fuel consumption**. The larger fan diameter required repositioning and enlarging of the engine, which drove several airframe changes.

---

## LEAP-1B vs CFM56-7 — Key Parameters

| Parameter | LEAP-1B | CFM56-7 |
|-----------|---------|---------|
| Fan diameter | **1.75 m (69")** | 1.55 m (61") |
| Fan blades | **18** (carbon fibre composite) | 24 |
| Bypass ratio | **9:1** | 5:1 |
| HP Compressor ratio | **22:1** | 11:1 |
| Weight (per engine) | +385 kg vs CFM56-7 | Reference |
| EGT T/O limit | 1038°C | 950°C |
| N1 max | 104.3% / 4,586 RPM | 104% / 5,382 RPM |
| N2 max | 117.5% / 20,171 RPM | 105% / 15,183 RPM |
| Fuel saving | **~15%** | Reference |
| Material saving | ~230 kg per engine vs conventional | — |

---

## Engine Architecture

- **Low Pressure Compressor (N1)**: 3 stages
- **High Pressure Compressor (N2)**: 10 stages
- **High Pressure Turbine (N2)**: 2 stages — ceramic composite shroud
- **Low Pressure Turbine (N1)**: 5 stages — **titanium aluminium** blades
- Twin-Annular, Pre-Mixing Swirler Combustor **(TAPS II)** → pre-mixes fuel and air → lean burn combustion
- New **debris rejection system** prevents sand/substances from reaching engine core
- During engine shutdown: Variable Stator Vanes (VSV) open and Variable Bleed Valves (VBV) close → audible engine noise is normal

---

## Thrust Rating Options

- **LEAP-1B25** ≈ 25k lbs
- **LEAP-1B27** ≈ 26.4k lbs
- **LEAP-1B28** ≈ 27.9k lbs

### Variable Thrust Rating (VTR)
> [!note] MAX-specific feature
> Unlike 737 CL/NG, MAX operators can customise **two derate thrust levels** (VTR):
> - VTR range: **1% – 30%**
> - Default derates: **10%** and **20%**
> - Climb derates TO-1 (10%) and TO-2 (20%) cannot be customised

---

## Chevrons (Noise Reduction)

- Located at the rear of the engine casing
- Improve mixing of the jet stream and ambient air → reduced turbulence → **reduced noise**

---

## Engine Starting

> [!warning] BRM — Bowed Rotor Motoring (ground starts only)
> Thermal bowing affects all jet engines after shutdown due to uneven heat distribution. BRM straightens the rotor before fuel is introduced.

| Starting Parameter | Value |
|-------------------|-------|
| Total ground start time | ~90 seconds (mainly due to BRM) |
| Starter cutout | 63% N2 |
| Stabilised idle | ~66% N2 (slower than CFM56-7) |
| Normal start duty cycle limit | **3 minutes** |
| Extended motoring limit | **5 minutes** → then 5 min OFF (1st two attempts), 10 min OFF (3rd+) |
| Min warmup before T/O | **3 min** (FCOM) / 5 min cold engines (CFM recommendation) |
| Oil temp required before T/O thrust | ≥ 31°C/88°F |
| Battery starts | **NOT available** on 737 MAX |

### BRM Process
- EEC keeps ~23% N2 during ground start for 6–90 seconds
- BRM stage annunciated as **"MOTORING"** on N2 indication (N2 > 18%)
- N2 speed controlled by modulation of start valve to **18–24%**
- Fuel flow and ignition **inhibited** during BRM
- BRM phase ends when "MOTORING" indication on N2 blanks
- **BRM works only for ground engine starts**

### BRM Duration Depends On:
- Engine residual temperature (T3) — hotter = longer BRM
- How long engine was shut down for
- Sensed engine vibration levels during BRM phase

### EGT Start Limits

| Start Type | EGT Limit |
|-----------|-----------|
| Ground start | **753°C** |
| Starter Assist / Steady State Windmill | 883°C |
| Quick Windmill Relight | 920°C |
| High Power Fuel Cut | 981°C |

---

## EEC Start Protections

| Condition | EEC Action |
|-----------|-----------|
| Hung Start (ground) | Increases fuel flow to reach idle |
| Hot Start (in-flight) | Stops fuel flow and ignition for 1.2 sec |
| Stall during in-flight start | Stops fuel flow and ignition for 1.2 sec |

> [!warning] In-flight windmill start
> QRH instructs to switch OFF the **affected side engine-driven hydraulic pump (EDP)** before windmill start. EDP friction greatly influences windmill speed (N2 may drop to 0%).

> [!info] EEC auto-abort on ground
> If start is automatically aborted by EEC, the EEC adapts fuel flow schedule for the next start-up. CFM recommends crew abort the next start attempt.

---

## Reverse Thrust

- More effective on LEAP-1B due to **higher bypass ratio** (more air reversed)

### New Aft Overhead Panel Warnings

| Light | Meaning |
|-------|---------|
| **REVERSER LIMITED** | Failure in reverser system — reverser limited to reverse idle or will not deploy |
| **REVERSER AIR/GROUND** | Air/ground thrust reverser logic failed — caution: reverser may deploy in-flight |
| **REVERSER COMMAND** | One of the reverse thrust levers not in stowed position in flight |

---

## LEAP-1B Engine Protections (New)

> [!note] Two new EEC system features — tested every engine start
> Both EOS and TCMA are tested during each engine start. During the test, the engine fuel shutoff valve repeatedly opens and closes → indicated by steady bright **ENG VALVE CLOSED** light with 0 Fuel Flow for a couple of seconds when engine start lever moved to IDLE.

### Electronic Overspeed System (EOS)

| Scenario | Action |
|----------|--------|
| N2 Overspeed | EOS shuts down engine |
| N1 Overspeed | EEC opens Variable Stator Vanes to trigger N2 overspeed → EOS shuts down engine |

Operates in both Normal and Alternate EEC modes.

### Thrust Control Malfunction Accommodation (TCMA)

| Scenario | Action |
|----------|--------|
| Engine does not respond to commanded deceleration | TCMA shuts down the engine (high asymmetric thrust protection) |
| Operational conditions | **Ground only** (RTO and flare) |

### Over-Thrust Protection

When thrust levers are at forward stop:
- First **15 minutes**: Maximum Take-off Thrust
- After **15 minutes**: Maximum Go-around Thrust
- Above FL190 or >M0.4: EEC restricts to **Maximum Continuous Thrust**
- After descend back: Maximum Take-off Thrust no longer available

---

## Related
- [[Anti-Ice]] — Icing Idle, Core Anti-Ice
- [[APU]] — APU changes
- [[Air Systems]] — bleed air from LEAP-1B
- [[Fuel/Quick-Reference/Key Numbers]]
