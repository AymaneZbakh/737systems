---
tags: [B737MAX, MAX-8, fuel, FQIS, FMC, FUEL-DISAGREE, fuel-capacity]
system: Fuel
---

# ⛽ MAX-8 Fuel
🔗 [[Home - MAX Differences]] | [[Landing Gear|← Landing Gear]] | [[Displays and AFDS|Next: Displays & AFDS →]]

> [!abstract] Overview
> The 737 MAX features new information and warnings related to the fuel system. Tank capacity has slightly decreased due to wing strengthening. New fuel alerts (FUEL DISAGREE, FUEL FLOW, FILTER BYPASS) and a new FMC FUEL PROGRESS page 5 provide enhanced awareness.

---

## Fuel Tank Capacity Changes

> [!warning] Slightly reduced capacity
> Wing strengthening required for the MAX resulted in a slight reduction in fuel tank capacity.

| Tank | MAX-8 (kg) | Δ vs NG | MAX-8 (L) | Δ vs NG |
|------|-----------|---------|----------|---------|
| No. 1 | 3,869 | −46 kg | 4,819 | −57 L |
| No. 2 | 3,869 | −46 kg | 4,819 | −57 L |
| Center | 12,990 | −76 kg | 16,179 | −94 L |
| **Total** | **20,728** | **−168 kg** | **25,817** | **−208 L** |

---

## New Fuel Alerts

### FUEL DISAGREE

> [!warning] New alert — scratchpad and message
> FUEL DISAGREE scratchpad message and alert illuminates when the fuel quantity calculated by the **FQIS** and **FMC** continuously disagree by approx. **907 kg (2,000 lbs)** for more than **5 minutes**.

- The difference can be viewed on the **FMC FUEL PROGRESS page 5**
- Also appears as an **amber alert** below the fuel quantity indication
- QRH non-normal checklist added to establish whether fuel leak is the cause

### FUEL FLOW

- Displayed on the engine instrument display
- FMC calculates the normal fuel flow estimate and compares it to the actual fuel flow
- When actual fuel flow is **abnormally high** (15% more than FMC calculation for continuous 5 minutes) → **FUEL FLOW** alert illuminates

### FILTER BYPASS

- If **both** FILTER BYPASS lights illuminate, they will stay illuminated until engine shutdown on the ground

### Additional Alerts

The following scratchpad messages now appear also **below the fuel quantity indication** as **amber alerts**:
- USING RESERVE FUEL
- INSUFFICIENT FUEL
- FUEL DISAGREE

---

## FMC FUEL PROGRESS Page 5 (New)

> [!info] New FMC page
> There is a new progress page 5 with additional fuel data.

| Data Field | Description |
|-----------|-------------|
| **APU FUEL USED** | Shows fuel burned by the APU since engine start |
| **FUEL QTY TOTALIZER** | Fuel quantity as calculated by FQIS (default) — if selected, SENS shown next to fuel on PERF INIT |
| **FUEL QTY CALCULATED** | Fuel quantity calculated by FMC (takes FQIS data at engine start, updates with EEC and APU fuel flow) — if selected, CALC shown next to fuel on PERF INIT |

---

## Related
- [[Engines]] — EEC provides fuel flow data
- [[APU]] — APU fuel used tracked
- [[Flight controls/Quick-Reference/Warning Lights]]
