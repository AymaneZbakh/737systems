---
tags: [air-conditioning, component, distribution, recirculation]
system: Air Conditioning
parent: "[[02-Air-Conditioning/Air Conditioning System]]"
---

# 🌬 Air Distribution

🔗 [[Home - Air Systems]] | [[02-Air-Conditioning/Air Conditioning System|Air Conditioning]] | [[Zone Temperature Control|Zone Temp →]]

> [!abstract] Overview
> Conditioned air from both packs flows into the Mix Manifold, then via riser ducts to overhead distribution, and is exhausted through floor grilles. Recirculation fans recycle ~50% of cabin air through HEPA filters.

---

## ⚙️ Supply Flow Path

```
L PACK ──► MIX MANIFOLD ◄── R PACK
              │
         ┌────┴─────┐
    TRIM AIR      RISER DUCTS (L & R sidewalls)
                       │
              OVERHEAD DISTRIBUTION DUCTS
                       │
              OUTLETS (sidewalls + cabin centre)
                       │
              FLOOR GRILLES (exhaust)
                    ┌──┴──┐
              OVERBOARD   RECIRCULATION
              (Outflow    FANS (L & R)
               Valve)          │
                          HEPA FILTERS
                               │
                          MIX MANIFOLD
```

---

## 📋 Pack Distribution Roles

| Pack | Primary Supply |
|------|---------------|
| Left Pack | **Flight deck** + excess to mix manifold |
| Right Pack | **Mix manifold** only (normally) |
| L Pack INOP | Flight deck gets conditioned air from R pack via mix manifold |

> [!note] Cabin Air Flow Direction
> Cabin air flows **backwards** (toward tail) due to outflow valve position. When transporting dogs and cats together, place the dog **forward** (upstream of the cat).

---

## 🔄 Recirculation Fans

| Parameter | Value |
|-----------|-------|
| Number of fans | 2 (Left & Right) |
| Filter type | **HEPA** (High-Efficiency Particulate Air) |
| When both ON | ~50% air recycled, ~50% fresh from packs |
| Power | AC motors |
| Cargo fire (QRH) | Both recirc fans **OFF** |

### Recirculation Fan Shutdown Logic

| Condition | L RECIRC shuts down | R RECIRC shuts down |
|-----------|--------------------|--------------------|
| **Ground** | Both packs in HIGH | **Never** |
| **In-flight** | Either pack in HIGH | Both packs in HIGH |

---

## 🔗 Related
- [[02-Air-Conditioning/Air Conditioning System|Air Conditioning System]]
- [[Packs|Packs]]
- [[Zone Temperature Control|Zone Temperature Control]]
- [[Equipment Cooling|Equipment Cooling]]
- [[Ground Conditioned Air Connector|Ground Conditioned Air]]
