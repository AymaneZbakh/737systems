---
tags: [B737, flight-controls, flaps, slats, high-lift, FSEU, secondary]
system: Flaps & Slats
hydraulics: [Hyd-B, Standby]
---

# ⊳ Flaps & Slats
> [!abstract] Overview
> Secondary high-lift system. TE flaps and LE devices sequenced by FLAP lever via FSEU. Normally powered by Hyd B. Comprehensive protection: flap load relief, asymmetry, skew, uncommanded motion detection. Maximum deployment altitude: 20,000 ft.

🔗 [[Home - Flight controls]] | [[Yaw Control|← Yaw Control]] | [[Speed Brakes|Next: Speed Brakes →]]

---

## Sub-systems

| System | Page |
|--------|------|
| LE Devices | [[LE Devices]] |
| TE Flaps | [[TE Flaps]] |
| Alternate Extension | [[Alternate Extension]] |
| Flap Load Relief | [[Flap Load Relief]] |
| Autoslats | [[Autoslats]] |
| FSEU Protection | [[FSEU Protection]] |

---

## TE Flap Positions & LE Device Response

| TE Flaps | LE Slats (SFP) | LE Slats (NON-SFP) |
|----------|---------------|-------------------|
| 1° – 25° | EXT | EXT |
| 30° – 40° | FULL EXT | FULL EXT |
| 1° – 5° | — | EXT |
| 10° – 40° | — | FULL EXT |

> [!info] LE Device positions
> Krueger flaps (inboard) have **one extended position**.
> Slats (outboard) have **extended** (sealed LE) and **fully extended** (slotted LE) positions.

---

## Hydraulic Power Summary

| System | Normal Power | Alternate |
|--------|-------------|-----------|
| TE flaps | Hyd B (priority valve → LE first) | Electric motor |
| LE devices | Hyd B | Standby hyd |
| Autoslats | Hyd B | PTU → Hyd B (via Hyd A EDP) |

---

## Normal TE Flap Drive System

```
FLAP lever → cables → Summing Lever → Flap Control Unit
  → Hyd B (priority valve — LE devices get priority)
  → Flow limiter (limits speed of TE flap movement)
  → Flap Power Drive Unit (PDU) — hydraulic motor + electric motor
  → Torque Tubes (2 per TE flap, 8 total)
  → TE Flap Transmissions (2 per flap)
  → TE flap surfaces

Follow-up cables → opposing pressure on summing lever → stops drive when commanded position reached
```

---

## Flap Load Relief Speeds

| From → To | Retracts above | Re-extends below |
|---|---|---|
| 40° → 30° | 163 kts | 158 kts |
| 30° → 25° | 176 kts | 171 kts |
| 25° → 15° | 191 kts | 186 kts |
| 15° → 10° | 201 kts | 196 kts |
| 10° → 5° | 211 kts | 206 kts |

> [!note] SFP vs NON-SFP
> Flap load relief for NON-SFP: flaps 30° and 40° only.
> SFP (737-800): flaps 10° – 40°.

---

## Key Limits

| Parameter | Value |
|-----------|-------|
| Maximum altitude for flap extension | 20,000 ft |
| Flap lever gates | 15° (normal G/A) and 1° (single-engine G/A) |
| Alt flap duty cycle — wait after release | 15 seconds |
| Alt flap duty cycle — cooling after F0→F15→F0 | 5 minutes |
| Alternate extension time (full travel) | ~2 min 40 sec (vs ~40 sec normal) |
