---
tags: [fuel, pumps, suction-feed, overview]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[../01-Fuel-Storage-and-Feed/Overview|← Previous]] | [[../03-Fuel-Crossfeed-and-Shutoff/Overview|Next →]]

# ⚙️ 02 — Fuel Pumps & Suction Feed

> [!abstract] Overview
> Each tank uses two AC-powered fuel pumps, cooled and lubricated by the fuel passing through them. Center tank pumps output higher pressure so center tank fuel is consumed first. If pump pressure is unavailable, engines can draw fuel by suction feed.

## 📋 Pump Comparison

| Parameter | Main Tank Pumps | Center Tank Pumps |
|---|---|---|
| Quantity | 2 per tank | 2 |
| Output pressure | 10 psi | 23 psi (higher — used first) |
| Flow rate | 9,071 kg/h (20,000 lb/h) | 9,071 kg/h (20,000 lb/h) |
| Power source | Transfer buses (AC) | Transfer buses (AC) |
| LOW PRESSURE threshold | < 4 psi, or switch OFF | < 22 psi, with switch ON |
| Master Caution delay | Per RECALL logic (see below) | 10-second delay |
| Auto-shutoff feature | — | Certain models: shuts off 15 s after LOW PRESSURE detected |
| Discharge check valve | ✅ Yes — prevents backflow from feed manifold | ✅ Yes |

> [!note] Why Center Tank Fuel Goes First
> Center tank pumps are deliberately set to a **higher output pressure (23 psi vs 10 psi)** so that when all 6 pumps operate simultaneously, center tank fuel is drawn down before main tank fuel.

## 🚦 LOW PRESSURE Light Logic

| Scenario | Result |
|---|---|
| One Main pump LOW PRESSURE light illuminated | Master Caution + FUEL annunciator on **RECALL** |
| Both Main pump LOW PRESSURE lights illuminated (same tank) | Master Caution + FUEL annunciator illuminate directly |
| One Centre pump LOW PRESSURE light, continuous 10 s | Master Caution + FUEL annunciator illuminate |
| Centre pump auto-shutoff (certain models) | Restart by cycling pump switch OFF then ON |

> [!warning] Flickering Lights Are Normal in Some Cases
> Fuel pump LOW PRESSURE lights may **flicker** when tank quantity is low combined with climb, descent, or nose-down ground attitude. For center tank pumps in cruise, low-pressure indication can occur even **after quantity reads zero**, and flickering can continue for up to **5 minutes** before Master Caution/FUEL annunciator illuminate.

## 🌀 Suction Feed

See [[Components/Suction-Feed|Suction Feed]] for full details, including flameout altitude and QRH guidance.

| Parameter | Value |
|---|---|
| Trigger | Main tank pump pressure low |
| Mechanism | Engine draws fuel via line that bypasses pumps |
| Risk | Dissolved air release during climb → restricted fuel flow |
| Flameout may occur as low as | 13,000 ft during high rate of climb |
| Recovery | Fuel flow should stabilise in a few minutes; maintain low ROC; action QRH |

## 🧭 Components in This Section

| Page | Summary |
|---|---|
| [[Components/Main-Tank-Fuel-Pumps\|Main Tank Fuel Pumps]] | Pressure, flow, LOW PRESSURE logic |
| [[Components/Center-Tank-Fuel-Pumps\|Center Tank Fuel Pumps]] | Pressure, auto-shutoff, restart procedure |
| [[Components/Suction-Feed\|Suction Feed]] | Bypass mechanism, altitude risk, QRH |
| [[Components/Center-Tank-Fuel-Scavenge-Jet-Pump\|Center Tank Fuel Scavenge Jet Pump]] | Auto transfer to Main Tank 1 |
| [[Components/Fuel-Filter-Bypass\|Fuel Filter Bypass]] | Contaminated filter warning |

> [!info] Related
> Fuel crossfeed and shutoff valves are covered in [[../03-Fuel-Crossfeed-and-Shutoff/Overview|03 — Fuel Crossfeed & Shutoff]].
