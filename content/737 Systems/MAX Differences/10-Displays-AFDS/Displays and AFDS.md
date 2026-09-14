---
tags: [B737MAX, MAX-8, displays, MDS, DPC, AFDS, EFIS, auxiliary-display]
system: Displays-AFDS
---

# 🖥 MAX-8 Displays, Instruments & AFDS
🔗 [[Home - MAX Differences]] | [[Fuel|← Fuel]]

> [!abstract] Overview
> The most noticeable difference in the flight deck is the four new **15.1 inch displays**. DEUs are replaced by Display Processing Computers (DPCs), forming the **MAX Display System (MDS)**. The AFDS also has changes related to stick shaker and low-speed behaviour.

---

## MAX Display System (MDS)

| Component | NG | MAX |
|-----------|-----|-----|
| Display size | ~8" | **15.1 inch** |
| Display units | 4× DEUs | 4× DUs with **2× DPCs** |
| Flap position indicator | Separate indicator | Now on **MFD** (with engine instruments) |
| Auxiliary display | Not present | **New — outboard of PFDs** |

> [!note] DPC operation
> DPCs operation is identical to the DEUs on NG. DPCs + new EFIS control panels + new larger DUs = **MAX Display System (MDS)**.

---

## Inboard Display Failure

| Failure | Result |
|---------|--------|
| Inboard DU failure | On-side PFD compass becomes a **mini-map** (contains most ND information) |
| Engine Display failure | Transfers to **opposite inboard DU** |

---

## EFIS Control Panel Changes

- Now has a dedicated **VSD switch**
- Map Range Selector now has **+/− range without numbers** — selected range displayed on ND (**0.5–640 NM**)

---

## Auxiliary Display (New on MAX)

> [!info] Located outboard of the PFDs
> The Aux display shows data relevant to the current flight:

- Flight number
- Transponder code
- SELCAL
- Chronometer, Elapsed time, and UTC times

### Chronometer Behaviour
- **Elapsed time starts** at lift-off (automatic)
- **Elapsed time stops** at touchdown + 30 seconds (automatic)
- New **Clock switch** at each end of the glareshield panel — starts, stops, and resets the chronometer

---

## Engine Display Control Panel

| Button | Function |
|--------|----------|
| **ENG** | Same function as NG |
| **SYS** | Same function as NG |
| **INFO** | Brings up the **N1/SPD REF SET page** to set N1 targets and V speeds |
| **C/R** | Cancel/Recall — cancels or recalls autoland advisory messages *(fail-operational autoland only)* |
| **ENG TFR** | Transfers engine instruments between inner DUs |

---

## AFDS Changes

> [!warning] Stick shaker + pitch mode behaviour
> When the stick shaker activates and the AFDS is in a pitch mode that doesn't have minimum speed reversion:

1. **A/P disengages** (one second delay)
2. **F/Ds are removed** (one second delay)
3. **F/Ds pop-up** when speed returns above lower amber band
4. When speed recovered, AFDS may return to a **different mode**:

| Previous Mode | Reverts To |
|--------------|-----------|
| ALT HOLD, VNAV ALT, VNAV PTH (level segment) | MCP SPD pitch |
| G/S, VS (>F15), GP, VNAV PTH (>F15) | Remains in previous mode |

- **A/P nose up trim** is inhibited when within lower amber band

---

## Cargo Compartments

| Hold | Capacity vs 737-800 |
|------|---------------------|
| Hold 1 | **−15%** lower volume |
| Hold 4 | **−25%** lower volume |
| **Overall** | **−3%** (total) |

### Cargo Fire Suppression

| Feature | NG | MAX |
|---------|----|-----|
| Fire extinguishing bottles | 1 | **2** |
| 2nd bottle discharge (in-flight) | After 60 min | After **15 minutes** |
| Total protection duration | Same | **195 minutes** (unchanged) |

---

## Related
- [[Flight Controls]] — AFDS interactions with MCAS
- [[Flight controls/Quick-Reference/Warning Lights]]
- [[Fuel/Quick-Reference/Key Numbers]]
