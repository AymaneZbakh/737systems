---
tags: [B737MAX, MAX-8, MCAS, AOA, sensors]
parent: "[[Flight Controls]]"
---

# AOA Sensors — MCAS Input
🔗 [[Flight Controls|← Flight Controls]]

> [!abstract]
> MCAS takes AOA data from **both AOA vanes**. The FCC compares inputs from the two sensors. Small differences are filtered to provide a single corrected AOA value to MCAS.

---

## Dual AOA Logic

| Condition | Result |
|-----------|--------|
| Small difference between sensors | Filtered — single corrected value used |
| Difference ≥ **5.5°** | FCC disables STS and MCAS for remainder of flight; SPEED TRIM FAIL illuminates |
| Difference ≥ **10°** | **AOA DISAGREE** alert illuminates |

---

## AOA Disagree Alert

- Illuminates when the difference between the AOA sensors is more than **10 degrees**
- This is a separate threshold from the 5.5° that disables MCAS

---

## Related
- [[Flight Controls]] — MCAS full description
- [[Flight controls/Quick-Reference/Warning Lights]]
