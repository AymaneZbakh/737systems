---
tags:
  - B737
  - flaps
  - FSEU
  - asymmetry
  - skew
  - uncommanded-motion
  - protection
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# FSEU Protection
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> The Flap/Slat Electronics Unit (FSEU) continuously monitors LE and TE device positions using 8 TE flap skew sensors and 2 TE flap position transmitters. Provides four types of protection: load relief, asymmetry, skew, and uncommanded motion.

---

## FSEU Data Sources

| Sensor | Count | Purpose |
|--------|-------|---------|
| TE flap skew sensors | 8 | Detect skew condition |
| TE flap position transmitters | 2 | Detect asymmetry condition |
| LE sensors | Multiple | Monitor LE device position |
| Left ADIRU (IAS) | 1 | Flap load relief input |

> [!note]
> The LE device annunciator panel (aft overhead), Flap Position Indicator, and LE FLAPS lights are all commanded by the FSEU.

---

## Protection Type 1 — Asymmetry

**Definition**: LE or TE flaps do not deploy symmetrically (left vs right).

| Detail | Value |
|--------|-------|
| Detection | TE position transmitters — needles split on indicator |
| Action | FSEU moves TE bypass valve to **bypass** → stops hydraulic TE drive |
| Indicator | Flap position indicator: **Left and Right needles show precise position per side** |
| QRH | "Trailing Edge Flap Asymmetry" |

> [!warning]
> FSEU asymmetry protection is **NOT available** when operating in ALTERNATE mode.

---

## Protection Type 2 — Skew

**Definition**: A TE flap panel twists during extension or retraction (inboard and outboard ends do not align).

| Detail | Value |
|--------|-------|
| Detection | TE flap skew sensors — 8 sensors monitor twist |
| Action | FSEU moves TE bypass valve to **bypass** → stops hydraulic TE drive |
| Indicator | Flap position indicator: **skewed side needle moves slightly away (~15°) from commanded position** |
| QRH | Same "Trailing Edge Flap Asymmetry" checklist |

> [!warning]
> FSEU skew protection is **NOT available** when operating in ALTERNATE mode.

---

## Protection Type 3 — Uncommanded LE Motion

**Definition**: Two or more LE flaps or two or more LE slats move on **one wing** without command.

| Detail | Value |
|--------|-------|
| Action | FSEU **shuts down LE control** → illuminates LE FLAPS TRANSIT |
| Cruise prevention | FSEU maintains pressure on retract lines and depressurises extend/full-extend lines when: flap lever UP + all LE flaps retracted + at least 7 LE slats retracted (for 5 seconds) |

---

## Protection Type 4 — Uncommanded TE Motion

**Definition**: TE flap moves away from commanded position, continues moving when reaching commanded position, or moves in opposite direction.

| Detail | Value |
|--------|-------|
| Indicator | **No flap needle split** (unlike asymmetry) |
| Action | FSEU shuts down TE drive unit by closing **TE flap bypass valve** |
| Reset | **Cannot be reset by flight crew** |
| Recovery | Must use [[04-Flaps-Slats/Alternate Extension|Alternate Flaps]] to control TE flaps |
| QRH | "TE Flap Disagree" |

---

## Stall Warning Enhancement

> [!info]
> When asymmetry, skew, or uncommanded motion is detected:
> - Stall warning is enabled at a **lower AOA threshold**
> - Provides earlier warning with degraded flap configuration

---

## LE Devices Annunciator Panel (Aft Overhead)

The LE Devices Annunciator Panel shows individual LE device status:
- **TRANSIT** (amber): device in transit
- **EXT** (green): device at extended position
- **FULL EXT** (green): device at full extended position

---

## Related
- [[Alternate Extension]]
- [[Flap Load Relief]]
- [[LE Devices]]
- [[Flight controls/Quick-Reference/Warning Lights]]
