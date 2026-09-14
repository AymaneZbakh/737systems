---
tags: [summary, overview, all-systems]
parent: Home
---

# 📋 System Overview — All Air Systems

🔗 [[Home - Air Systems]] | [[Fuel/Quick-Reference/Key Numbers|Key Numbers →]]

> [!abstract] Overview
> Consolidated one-page reference for all three Air Systems: Bleed Air, Air Conditioning, and Pressurisation.

---

## 🌬 Bleed Air System — Key Facts

| Topic | Detail |
|-------|--------|
| Sources | Engine (5th/9th stage), APU, Ground Pneumatic |
| Key valve | PRSOV (butterfly, DC activated, pressure operated, spring-closed) |
| PRSOV limits | 42 psi / 232°C (450°F) |
| Bleed Trip-Off triggers | Over-temp >254°C / Over-pressure >220 psi |
| Precooler output target | 199–229°C (390–440°F) |
| 9th stage regulated range | 26–47% N1 → 32 psi ±6 |
| 5th stage regulated range | >54% N1 → 42 psi ±8 |
| Isolation valve normal pos | CLOSED (separates L/R manifolds) |
| APU bleed only max alt | 17,000 ft |
| APU bleed + electric max alt | 10,000 ft |
| External source max | 60 psi / 232°C |
| High duct pressure (maint) | >50 psi |
| WING-BODY OVERHEAT sensor power | 115V AC required |

---

## ❄️ Air Conditioning System — Key Facts

| Topic | Detail |
|-------|--------|
| Number of packs | 2 (L and R) |
| Pack main components | FCSV, ACM (compressor + turbine), Primary & Secondary HX |
| Pack normal flow (2 packs) | 55 lb/min |
| Pack HIGH flow | 100 lb/min |
| Pack/Zone Controllers | 2 (cross-cover each other) |
| Temperature zones | 3: CONT CAB (FD), FWD CAB, AFT CAB |
| Zone temp range | 18°C–30°C (65°F–85°F) |
| Balanced mode | Both packs same temp; coldest zone drives pack output |
| Unbalanced mode | Flight deck trim air fails; L pack→FD, R pack→cabin coldest |
| Unbalanced average | TRIM AIR OFF or zone fails; L pack→FD, R pack→average of 2 cabin zones |
| Recirculation | 2 HEPA fans; ~50% recycled when both on |
| L recirc fan shuts (ground) | Both packs HIGH |
| L recirc fan shuts (flight) | Either pack HIGH |
| R recirc fan shuts (flight) | Both packs HIGH |
| Equipment cooling fans | NORM + ALTN (115V AC), one at a time |
| Exhaust routing | <2 psi diff → overboard; pressurised → FWD cargo floor |

---

## 🔵 Pressurisation System — Key Facts

| Topic | Detail |
|-------|--------|
| Controllers | 2 CPCs, swap roles each flight |
| CPC power | DC BUS #1 & #2 |
| Outflow valve motors | 3 (CPC1, CPC2, Manual/BAT BUS) |
| OFV location | Below right horizontal stabiliser |
| Manual mode speed | 20 sec full travel (faster than auto) |
| Normal cabin rate | ≤750 FPM |
| Diff press ≤FL280 | 7.45 psi |
| Diff press FL280–FL370 | 7.80 psi |
| Diff press >FL370 | 8.35 psi |
| Positive relief valves | 2× open at 9.1 psi |
| Negative relief valve | 1× opens at −1.0 psi |
| Cabin altitude warning | 10,000 ft (same sound as T/O warning) |
| OFV safety close | >14,500 ft cabin alt (CPC mode only) |
| Uncontrollable cabin definition | Rate >750 FPM in AUTO/ALTN, cannot control manually, OR cabin alt ≥15,000 ft |
| AUTO FAIL high cabin alt trigger | >15,800 ft |
| AUTO FAIL excess diff press trigger | >8.75 psi |
| AUTO FAIL excess rate trigger | >2,000 FPM |
| Blowout panels FWD/AFT | 2× / 3× |

---

## 🔀 System Interdependencies

| Scenario | Effect Across Systems |
|----------|-----------------------|
| Both packs OFF | No fresh air → cabin gradually depressurises |
| PACK BLEED TRIP-OFF | Manual pressurisation may be required |
| Loss of all AC power | Pressurisation must be manual (DC buses de-powered → CPC motors offline) |
| Equipment cooling disruption | Can signal impending pressurisation problems |
| Wing-Body Overheat | Watch for A/C or PRESS failures on **opposite** side |
| Cargo fire (QRH) | Both recirc fans OFF |
| L Pack INOP | Flight deck gets air from R pack via mix manifold |

---

## 🔗 All System Pages

| System | Main Page |
|--------|-----------|
| Bleed Air | [[01-Bleed-Air-System/Bleed Air System]] |
| Air Conditioning | [[02-Air-Conditioning/Air Conditioning System]] |
| Pressurisation | [[03-Pressurisation/Pressurisation System]] |
| Key Numbers | [[Fuel/Quick-Reference/Key Numbers]] |
| Warning Lights | [[Fuel/Quick-Reference/Warning Lights]] |
| Abbreviations | [[Fuel/Quick-Reference/New Abbreviations]] |
