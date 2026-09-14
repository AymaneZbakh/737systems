---
tags: [B737MAX, quick-reference, warnings, lights, cautions]
---

# ⚠️ Warning Lights — MAX-8 Differences
🔗 [[Home - MAX Differences]] | [[Flight controls/Summary/System Overview]]

> New lights, renamed lights, or lights with different logic on the MAX-8 vs NG.

---

## New Lights on MAX-8 (not on NG)

| Light | System | Illuminates When |
|-------|--------|-----------------|
| **EQUIP SMOKE** | Air Systems | Smoke detected in equipment cooling system |
| **DOOR** (APU) | APU | APU door not in commanded position for 165 sec / door stays open after APU shutdown |
| **REVERSER LIMITED** | Engines | Failure in reverser system — limited to idle reverse or will not deploy |
| **REVERSER AIR/GROUND** | Engines | Air/ground reverser logic failed — reverser may deploy in-flight |
| **REVERSER COMMAND** | Engines | A reverse thrust lever not stowed in flight |
| **SPOILERS** | Spoilers | Fault in spoiler system detected by SCE Unit |
| **ASSIST ON** | Spoilers | EJLA (Elevator Jam Landing Assist) is active |
| **AOA DISAGREE** | Flight Controls | AOA sensor difference ≥ 10° |
| **TIRE PRESSURE** (Option) | Landing Gear | Pressure < 100 psi / >25% difference (main) / >12% difference (nose) |

---

## Renamed / Changed Lights

| NG Light | MAX Light | Notes |
|----------|-----------|-------|
| COWL VALVE OPEN | **COWL VALVE** | Engine TAI valve status |
| L/R VALVE OPEN | **L/R VALVE** | Wing WAI valve status |
| BLEED TRIP OFF | **BLEED** | Single light (was two on NG) |
| PSEU | **MAINT** | General maintenance indication |
| MAIN ELEC (trim cutout) | **PRI** | Stab trim cutout |
| AUTO PILOT (trim cutout) | **B/U** | Stab trim cutout |

---

## Lights with Different Logic / Additional Conditions on MAX

| Light | Additional MAX Condition |
|-------|--------------------------|
| **SPEED BRAKE EXTENDED** | Also illuminates for: go-around thrust set for 3 sec; thrust above idle for 15 sec |
| **SPEED TRIM FAIL** | Also: MCAS max command limit reached; AOA sensor difference ≥ 5.5°; erroneous FCC trim detected |
| **STAB OUT OF TRIM** | Also: FCC cross trim monitor detected erroneous FCC (after landing, below 30 kts) |
| **ENG VALVE CLOSED** | Steady bright for a few sec at engine start lever to IDLE — normal (EOS/TCMA test) |

---

## BLEED Light — Detailed Logic (MAX)

| Condition | Single Light | Both Lights |
|-----------|-------------|-------------|
| Over-pressure (170 psi, 5 sec) | ✅ | — |
| Over-temperature (254°C, 20s) | ✅ | — |
| Under-pressure | ✅ | — |
| Fault in bleed system | ✅ | — |
| Both bleeds OFF 45 sec after T/O flap retraction | — | ✅ |
| Both bleeds OFF 10 min after flap retraction (no bleed landing) | Neither | Neither |

---

## PACK Light — Detailed Logic (MAX)

| Condition | Single Light | Both Lights |
|-----------|-------------|-------------|
| Overheat | ✅ | — |
| PACK Control failure (primary + standby) | ✅ | — |
| PACK Control Valve fails open | ✅ | — |
| Either primary or standby failure | MAINT on landing | — |
| Both PACK switches OFF 45 sec after T/O flap retraction | — | ✅ |

---

## Related
- [[Flight Controls]] — MCAS / SPEED TRIM FAIL
- [[Spoilers]] — SPOILERS / ASSIST ON / SPEED BRAKE EXTENDED
- [[Air Systems]] — BLEED / PACK / EQUIP SMOKE
- [[Engines]] — REVERSER lights / ENG VALVE CLOSED
- [[APU]] — DOOR light
