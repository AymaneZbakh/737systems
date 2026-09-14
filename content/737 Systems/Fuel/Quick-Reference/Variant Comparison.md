---
tags: [fuel, quick-reference, variant, comparison]
system: Fuel
parent: "[[Home]]"
---

🔗 [[Home]] | [[Warning Lights|← Previous]] | [[New Abbreviations|Next →]]

# 🆚 Variant Comparison

> [!abstract] Overview
> Royal Air Maroc's 737 fleet spans several tail-number ranges with different fuel-panel hardware and NGS fitment. This page compares the two major axes of difference: **refuel panel type** and **NGS installation status**.

## 🛩 Refuel Panel: Analog vs Digital

| Feature | Analog Panel (older) | Digital Panel (newer) |
|---|---|---|
| Tail ranges | CN-RGV, CN-ROH, CN-ROJ | CN-RGE–RGN, CN-RGW–ROE, CN-ROK–ROZ |
| Fuel quantity display | Round dial gauge, e.g. "2080 KG" | 5-digit numeric readout, e.g. "88888" |
| Valve Position Lights | ✅ Present | ✅ Present |
| Fuel Quantity Selector (set desired qty) | ❌ Not fitted | ✅ Rotary selector fitted |
| Fueling Indication Test Switch | ✅ Shared logic | ✅ Shared logic |

> [!note] Practical Impact
> On digital-panel aircraft, ground crew can **dial in** a target fuel quantity per tank and the system auto-shuts the fueling valve at that value. Analog-panel aircraft rely on gauge reading + manual valve switch timing.

## 🌬 NGS Installation Status

| Feature | NGS Installed & Active | NGS Deactivated |
|---|---|---|
| Tail ranges | CN-RGE–RGW, CN-ROS–ROZ | CN-RNP–ROR |
| Center tank O₂ reduction | ≈ 12% (active inerting) | None (ignition-source elimination only) |
| Wheel-well indicator lights | OPERATIONAL / DEGRADED / INOPERATIVE all meaningful | Panel present but system deactivated |
| Dispatch impact | MEL applies if inoperative | Already dispatched without active NGS by design |

## 🖥 Fuel Quantity Low-Alert Display Behaviour

| Feature | CN-RGE–RGV, CN-RNP–ROZ | CN-RGW |
|---|---|---|
| FUEL LOW display | Arc **and** digits turn amber | **Digits only** turn amber (no arc — digital display) |
| Total fuel quantity readout | Not shown separately | **Total shown** beneath individual tank quantities |

## 🔗 Related

- [[../05-Fueling-Defueling-Ground-Transfer/Components/Test-Gages-and-Fueling-Panel|Test Gages & Fueling Panel]]
- [[../06-Nitrogen-Generation-System/Components/NGS-Deactivated-Variant|NGS Deactivated Variant]]
- [[../04-Fuel-Quantity-Indication/Components/Fuel-Alerts|Fuel Alerts]]
