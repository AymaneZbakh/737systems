---
tags: [B737, yaw, standby-rudder, FFM, force-fight]
parent: "[[Yaw Control]]"
---

# Standby Rudder & Force Fight Monitor (FFM)
🔗 [[Yaw Control|← Yaw Control]]

> [!abstract]
> The FFM continuously monitors for opposing pressure between Hyd A and B actuators in the main PCU. Auto-activates standby rudder on detection. Can also be activated manually.

---

## Force Fight Monitor (FFM)

**Detects:** Opposing pressure between Hyd A and Hyd B actuators
**Cause:** Either system jammed or disconnected

### Auto-activation sequence

1. FFM detects opposing pressure
2. **Standby hydraulic pump** automatically turns ON
3. **Standby Rudder Shutoff Valve** opens → pressurises Standby Rudder PCU
4. **STBY RUD ON** light illuminates (amber)
5. **Master Caution** + **FLT CONT** lights illuminate

---

## STBY RUD ON Light

> [!warning] STBY RUD ON (Amber)
> Illuminates whenever the STBY HYD EMDP is **manually or automatically** commanded to pressurise the standby rudder PCU.
> Verify standby hydraulic system status on EICAS.

---

## Manual Activation

- FLT CONTROL switch → **STBY RUD** position (either A or B)
- Used if FFM fails to auto-activate, or during abnormal procedures

---

## Auto-Activation Phases

> [!info]
> Standby rudder system also auto-activates during **takeoff and landing** as a precautionary measure — providing immediate standby rudder availability.

---

## Related
- [[Rudder (RSEP)]]
- [[Yaw Damper]]
- [[Flight controls/Quick-Reference/Warning Lights]]
