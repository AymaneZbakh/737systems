---
tags: [electrical, power-distribution, component, gcu]
system: Electrical
parent: "[[03-Power-Distribution]]"
---

🔗 [[Fuel/Home]] | [[03-Power-Distribution|← Previous]] | [[BPCU|Next →]]

# 🔧 Generator Control Unit (GCU)

> [!abstract] Overview
> There are **two GCUs**, one per engine IDG. Each one polices the quality of its generator's output and manages the associated Generator Control Breaker (GCB) and Bus Tie Breaker (BTB).

## 📋 Key Facts

| Function |
|---|
| Controls on-side **Generator Control Breaker (GCB)** and **Bus Tie Breaker (BTB)** |
| Monitors power quality — trips GCB for under/over-frequency, under/over-voltage, overcurrent |
| Controls **excitation** of the IDG generator |
| Monitors associated transfer bus status — issues `SOURCE OFF` and `TRANSFER BUS OFF` warnings |

## 🎛 Engine Generator Switch

| Position | Behaviour |
|---|---|
| **ON** | Disconnects previous power source first (no paralleling) → connects IDG to related AC Transfer Bus by closing the GCB |
| **OFF** | Disconnects IDG from related AC Transfer Bus (opens GCB) → closes Bus Tie Breakers to power the AC Transfer Bus from the offside IDG (requires [[Bus-Transfer-Switch]] in AUTO) |

## 🎛 Bus Transfer Switch (summary)

> [!note] Full detail in [[Bus-Transfer-Switch]]
> Lets the flight crew override the BPCU's automatic bus power transfer feature. In **AUTO**, BTBs stay open while both IDGs power their own transfer bus (no paralleling), and close automatically if one loses power or a single source (APU/Ground) feeds both.

---
🔗 [[03-Power-Distribution]] · [[Transfer-Bus-Warning-Lights]] · [[Bus-Tie-Breakers]]
