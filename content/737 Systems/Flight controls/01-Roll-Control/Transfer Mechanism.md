---
tags: [B737, roll, transfer, jam, lost-motion]
parent: "[[Roll Control]]"
---

# Aileron Transfer Mechanism
🔗 [[Roll Control|← Roll Control]]

> [!abstract]
> Interconnects CPT and F/O control wheels to allow synchronised operation. Enables bypass of a jammed control system. Formed by: interconnecting cables, a torsion spring, and a Lost Motion Device.

---

## Components

| Component | Function |
|-----------|----------|
| Interconnecting cables | Link CPT and F/O control wheels |
| Torsion spring | Allows jam bypass — overcome with force |
| **Lost Motion Device** | Sequences spoiler inputs through aileron system; enables FO jam bypass |

---

## Lost Motion Device (LMD)

> [!info]
> During **normal operation**: LMD ensures F/O wheel inputs are sequenced through the aileron system path:
> `F/O wheel → CPT shaft → Aileron Spring Cartridge → Spoilers`
>
> During **CPT jam**: LMD requires **12° of F/O wheel rotation** to engage and transfer inputs around the jam.
> - This creates a **12° dead band** in roll when bypassing a CPT jam
> - After engagement, F/O controls roll via flight spoilers only

---

## Jam Logic

| Jam Location | Available Roll | Via |
|---|---|---|
| CPT aileron system jammed | F/O wheel + 12° dead band | Spoilers (via LMD + Spoiler Mixer) |
| F/O spoiler system jammed | CPT wheel + 3° dead band | Ailerons (via PCUs) |

> [!warning]
> If CPT jammed: expect 12° dead band before F/O spoiler roll authority begins.
> Overcome torsion spring force to bypass.

---

## Related
- [[Aileron Spring Cartridge]]
- [[Spoiler Mixer]]
- [[Ailerons]]
- [[Flight Spoilers]]
