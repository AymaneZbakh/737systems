---
tags: [pressurisation, component, outflow-valve, OFV]
system: Pressurisation
parent: "[[03-Pressurisation/Pressurisation System]]"
---

# ⚙️ Outflow Valve (OFV)

🔗 [[Home - Air Systems]] | [[03-Pressurisation/Pressurisation System|Pressurisation]] | [[CPC|← CPC]]

> [!abstract] Overview
> The Outflow Valve is the primary means of controlling cabin pressure. It modulates between open and closed to allow the correct amount of air to escape. Located below the right horizontal stabiliser.

---

## 📋 OFV Quick Facts

| Parameter | Value |
|-----------|-------|
| Location | Below right horizontal stabiliser |
| Noise reduction | Comb-like teeth at valve tip |
| Drive motors | **3** (triple-redundant) |
| Only one motor drives at a time | ✅ |
| Safety close (cabin alt >14,500 ft) | Closes automatically — CPC control only |
| Manual mode speed | **20 seconds** full travel (faster than auto) |
| Manual power source | **BAT BUS** |

---

## ⚙️ Motor Summary

| Motor | Mode | Power Source |
|-------|------|-------------|
| CPC 1 Motor | AUTO / ALTN | DC BUS #1 |
| CPC 2 Motor | AUTO / ALTN | DC BUS #2 |
| Manual Motor | MANUAL (toggle switch) | **BAT BUS** |

---

## 🔧 Manual OFV Operation

> [!warning] Manual Mode — Key Points
> - OFV travels **faster** in manual mode (designed for rapid depressurisation/evacuation)
> - Even a **short** toggle press can cause a **large** cabin altitude change
> - Toggle should **not** be held for more than **1 second** — avoid rapid pressurisation changes
> - Required OFV position **varies throughout flight** depending on bleed supply and air leakage
> - After every thrust change, OFV position may need adjustment (also with TAI/WAI use)

---

## 📋 Non-Normal Conditions Requiring Manual Control

| Condition | Reason |
|-----------|--------|
| Cabin Altitude Warning / Rapid Decompression | Emergency response |
| Tail Strike | Structural concern |
| PACK, BLEED TRIP-OFF, WING-BODY OVERHEAT | Reduced pressurisation ability |
| AUTO FAIL or Unscheduled Pressurisation Change (>750 FPM) | CPC failure |
| Loss of AC Power Sources (DC BUS 1 & 2 unpowered) | Both CPC motors lost |
| Landing Gear Won't Move Up After T/O | Air-ground sensor stuck → CPCs open OFV when thrust reduced |
| Cabin Temperature Hot | Thermal management |

---

## 🔗 Related
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
- [[CPC|CPC]]
- [[Manual Pressurisation|Manual Pressurisation]]
- [[Cabin Pressure Relief System|Cabin Pressure Relief System]]
