---
tags: [B737, pitch, STS, speed-trim, FCC, SMYD]
parent: "[[Pitch Control]]"
---

# Speed Trim System (STS)
🔗 [[Pitch Control|← Pitch Control]]

> [!abstract]
> Automatic speed stability augmentation — especially at low gross weight, aft CG, high thrust. Trims stabiliser to oppose any change in airspeed. Function of FCCs; uses A/P trim system. Only one FCC (normally FCC A) supplies the STS signal at a time.

---

## Activation Conditions (ALL required)

| Condition | Value |
|-----------|-------|
| A/P | NOT engaged |
| Speed | 100 kt – Mach 0.60 |
| Time after takeoff | 10 seconds |
| Time after trim release | 5 seconds |
| Trim requirement | Sensed |

---

## STS Logic

| Speed change | STS response |
|---|---|
| Speed **increases** (positive) | Trims stab **nose up** (opposes acceleration) |
| Speed **decreases** (negative) | Trims stab **nose down** (opposes deceleration) |

> [!info] High AOA mode
> As speed decreases to stick-shaker AOA at idle thrust, STS continues to trim nose-down above stick-shaker AOA.
> **STS High AOA Mode is enabled at ALL flap settings.**
> Once aircraft returns to trimmed airspeed, STS **reverses its inputs**.

---

## STS Stops When

- Roll angle > **40°**
- Stabiliser trim reaches its limit or exceeds aft column cutout position
- Manual trim applied (STS restarts if trim requirement still sensed **5 seconds** after release)

---

## Speed Range

| Range | Status |
|-------|--------|
| Below 100 KIAS | Inactive |
| 100 KIAS – Mach 0.60 | Fully active |
| Mach 0.60 – 0.68 | Fades linearly to zero |
| Above Mach 0.68 | Inactive |

---

## SPEED TRIM FAIL Light (Amber)

> [!warning]
> On recall = single Flight Control Computer (FCC) failure.
> Be aware of potential speed instability at low weight / aft CG / high thrust configurations.

---

## Related
- [[Mach Trim]]
- [[Stabilizer and Trim]]
- [[Stall Identification (EFS)]]
- [[Flight controls/Quick-Reference/Warning Lights]]
