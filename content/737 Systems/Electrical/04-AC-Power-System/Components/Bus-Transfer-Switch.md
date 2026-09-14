---
tags: [electrical, ac-power, component, bus-transfer-switch]
system: Electrical
parent: "[[04-AC-Power-System]]"
---

🔗 [[Fuel/Home]] | [[04-AC-Power-System|← Previous]] | [[Bus-Tie-Breakers|Next →]]

# 🔧 Bus Transfer Switch

> [!abstract] Overview
> Lets the flight crew override the [[BPCU]]'s automatic bus-power-transfer feature — determines whether Bus Tie Breakers and the Cross Bus Tie Relay are locked open or allowed to operate automatically.

## 🎛 AUTO Position

| Behaviour                                                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| When both IDGs supply the Transfer Buses,[[Bus-Tie-Breakers]] stay **open** — no paralleling of AC sources                                                      |
| BTBs **automatically close** when one Transfer Bus loses power, or when APU/Ground Power is the only AC source (both Transfer Buses then share the same source) |
| [[CBTR]] stays **normally closed** so the three TRs share the load equally                                                                                      |
| CBTR **opens** on G/S capture (F/D or A/P approach) to isolate DC busses — prevents a single failure from affecting both receivers                              |

## 🎛 OFF Position

> [!warning] OFF locks the buses apart
> | Effect |
> |---|
> | **Bus Tie Breakers** locked open — Transfer Bus 1 isolated from Transfer Bus 2 |
> | **DC Cross Bus Tie Relay** opens — DC Bus 1 isolated from DC Bus 2 |
> | **TR3** isolated from Transfer Bus 1 — Transfer Bus 2 powers TR3 |

---
🔗 [[04-AC-Power-System]] · [[Bus-Tie-Breakers]] · [[CBTR]] · [[Transfer-Bus-Warning-Lights]]
