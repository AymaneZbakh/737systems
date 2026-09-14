---
tags:
  - B737
  - flaps
  - alternate
  - standby
  - emergency
  - duty-cycle
parent: "[[Flight controls/04-Flaps-Slats/Flaps and Slats]]"
---

# Alternate Flap Extension
🔗 [[Flight controls/04-Flaps-Slats/Flaps and Slats|← Flaps & Slats]]

> [!abstract]
> Used when Hyd B is lost or normal flap system fails. TE flaps driven by electric motor in the Flap PDU; LE devices extended via standby hydraulic. No asymmetry or skew protection in alternate mode.

---

## Alternate Flaps Arm Switch

### ARM position
- Places TE flap bypass valve into **bypass position** (prevents hydraulic lock of flap drive unit)
- Activates **standby hydraulic pump**
- Arms the position switch

### Position Switch

| Switch | Position | Action |
|--------|----------|--------|
| DOWN (momentary) | — | Fully extends **LE devices** via standby hydraulic |
| DOWN (hold) | — | Electrically extends **TE flaps** (hold until desired position) |
| UP | — | Electrically **retracts** TE flaps |

---

## LE Devices in Alternate Mode

- Extended by momentarily selecting alternate flaps control switch to **DOWN**
- Powered by **Standby Hydraulic**
- **Cannot be retracted** by alternate flap system once extended

---

## TE Flaps in Alternate Mode

- Extended by **holding** the alternate flaps control switch in DOWN position
- Powered **electrically** (electric motor in Flap PDU)
- Full TE flap travel takes approximately **2 minutes 40 seconds** (vs ~40 seconds in normal mode)

---

## Duty Cycle Restrictions

> [!warning] Alternate flap duty cycle
> - After **releasing** the alternate flap position switch: wait **15 seconds** before moving it again
>   *(prevents damage to the alternate flap motor clutch)*
> - After a complete cycle from F0 → F15 → F0: allow **5 minutes cooling** before operating alternate flaps again

---

## Limitations

> [!warning]
> - **No asymmetry or skew protection** in alternate mode
> - LE devices **cannot be retracted** via alternate/standby system
> - Alternate extension significantly slower than normal
> - Monitor flap position indicator carefully

---

## When to Use

- Normal Hyd B flap drive failure
- Hyd B loss (with normal flap system inoperative)
- After FSEU uncommanded TE motion shutdown (bypass valve closed — cannot be reset)

---

## Related
- [[FSEU Protection]]
- [[LE Devices]]
- [[Hydraulic Power Sources]]
