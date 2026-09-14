---
tags: [pressurisation, component, CPC]
system: Pressurisation
parent: "[[03-Pressurisation/Pressurisation System]]"
---

# 🖥️ Cabin Pressure Controllers (CPC)

🔗 [[Home - Air Systems]] | [[03-Pressurisation/Pressurisation System|Pressurisation]] | [[Outflow Valve|OFV →]]

> [!abstract] Overview
> Two identical CPCs automatically control cabin pressure throughout the flight. Only one is active at a time; the other serves as backup. They swap roles each flight.

---

## 📋 CPC Quick Facts

| Parameter | Value |
|-----------|-------|
| Number | **2** (CPC 1 and CPC 2) |
| Active at a time | **1** |
| Backup role | Other CPC activates on failure (ALTN) |
| Power | CPC 1 → DC BUS #1 / CPC 2 → DC BUS #2 |
| Role swap | Every flight (AUTO → ALTN → AUTO) |
| Loss of all AC power | Must control manually (DC BUS #1 & #2 not powered → CPC motors not powered) |

---

## 📡 CPC Inputs

| Input Source | Data Provided |
|-------------|--------------|
| ADIRUs | Baro corrected altitude + non-corrected altitude |
| Air/Ground sensors | Ground / flight status |
| SMYD computers | Throttle position |
| Ambient static pressure sensors | Current atmospheric pressure |
| Calibrated airspeed | Speed data |

---

## ⚙️ CPC Control — OFV Motors

| Motor | Controlled By | Power |
|-------|--------------|-------|
| Valve Motor (CPC 1) | CPC 1 — AUTO/ALTN | DC BUS #1 |
| Valve Motor (CPC 2) | CPC 2 — AUTO/ALTN | DC BUS #2 |
| Valve Motor (Manual) | OFV Toggle Switch | **BAT BUS** |

> [!note] Manual Always Available
> Manual OFV control is powered from BAT BUS, ensuring pressurisation can be controlled even on standby power.

---

## 💡 AUTO FAIL Illumination Triggers

> [!warning] AUTO FAIL Conditions
> | Trigger | Threshold |
> |---------|----------|
> | DC power lost | — |
> | Controller fault | — |
> | Outflow valve control fault | — |
> | Excessive differential pressure | **> 8.75 psi** (no correction) |
> | Excessive cabin pressure change rate | **> 2,000 FPM** (no correction) |
> | High cabin altitude | **> 15,800 ft** (no correction) |

---

## 🔗 Related
- [[03-Pressurisation/Pressurisation System|Pressurisation System]]
- [[Outflow Valve|Outflow Valve]]
- [[Manual Pressurisation|Manual Pressurisation]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
