---
tags: [electrical, ac-power, component, warning-lights]
system: Electrical
parent: "[[04-AC-Power-System]]"
---

🔗 [[Fuel/Home]] | [[CBTR|← Previous]] | [[Ground-Power|Next →]]

# 💡 Transfer Bus Warning Lights

> [!abstract] Overview
> Three related lights tell the crew the health of the Generator Control Breaker and the associated AC Transfer Bus.

## 📋 Light Reference

| Light | Condition | Notes |
|---|---|---|
| **GEN OFF BUS** | Illuminates whenever the **Generator Control Breaker (GCB)** is open — not providing power to its Transfer Bus | Regardless of whether the IDG is running or not |
| **SOURCE OFF** | No source has been manually selected to power the related Transfer Bus, or the manually selected source has been disconnected | If the opposite Transfer Bus is powered, power transfers automatically through BTBs when [[Bus-Transfer-Switch]] is AUTO |
| **TRANSFER BUS OFF** | Related AC Transfer Bus does not have power | Monitored by the corresponding [[GCU]], which illuminates the light |

> [!warning] SOURCE OFF can mean a generator failure
> `SOURCE OFF` can indicate a **generator failure or engine shutdown** — always cross-check the engine instruments when it illuminates.

---
🔗 [[04-AC-Power-System]] · [[GCU]] · [[Bus-Transfer-Switch]]
