---
tags: [air-conditioning, component, pack-controller, zone-controller]
system: Air Conditioning
parent: "[[02-Air-Conditioning/Air Conditioning System]]"
---

# 🖥️ Pack/Zone Controllers

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|Air Conditioning]] | [[Zone Temperature Control|Zone Temp →]]

> [!abstract] Overview
> Two Pack/Zone Temperature Controllers manage both pack output temperature and the three cabin zone temperatures. Each controller has a primary and standby function, cross-covering the opposite pack.

---

## 📋 Controller Assignment

| Controller | Primary Control | Standby for | Zone Control |
|-----------|----------------|-------------|-------------|
| L Pack Controller | L PACK | R PACK (standby) | AFT CAB zone + STANDBY CONT CAB |
| R Pack Controller | R PACK | L PACK (standby) | FWD CAB zone + PRIMARY CONT CAB |

> [!note] Cross-Coverage
> The L Pack Controller is R Pack's standby. The R Pack Controller is L Pack's standby. Also includes RAM AIR control for their respective side.

---

## ⚙️ Control Logic

| Function | Description |
|----------|-------------|
| Zone comparison | Controllers compare all 3 zone temperature requirements |
| Pack output temp | Set to satisfy the zone requiring the **most cooling** |
| Temperature Control Valve | Pack/Zone Controllers open/close this valve to regulate pack output |

---

## 💡 PACK Light — Controller Failure

| Condition | PACK Light | Action |
|-----------|-----------|--------|
| Primary pack control failure | ON RECALL | Pack continues (standby controls temp valve) |
| Both primary AND standby fail | Illuminated, **cannot be reset** | Pack runs uncontrolled until overheat trips it off |

> [!warning] Both Controllers Failed
> If both primary and standby pack controls fail, the pack continues operating but with no temperature control. It will run until an overheat condition causes automatic trip-off.

---

## 🔗 Related
- [[02-Air-Conditioning/Air Conditioning System|Air Conditioning System]]
- [[Packs|Packs]]
- [[Zone Temperature Control|Zone Temperature Control]]
- [[Fuel/Quick-Reference/Warning Lights|Warning Lights]]
