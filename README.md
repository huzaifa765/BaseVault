# 🔵 BaseVault — On-Chain Savings Protocol

> A personal savings goals protocol deployed on Base mainnet. 
> Set goals, lock ETH, track progress — fully onchain.

![Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-0.8.20-363636?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🎯 Problem It Solves

Most people save money in banks with zero transparency.
BaseVault brings savings onchain — every goal, every deposit, 
every milestone is recorded on Base blockchain forever.

No middleman. No bank. Just your wallet and your goals.

---

## ✨ Features

- 🎯 **Multiple Goals** — Create unlimited savings goals
- 📊 **Progress Tracking** — See % completion onchain
- ⏰ **Deadline Setting** — Set target dates for goals
- 🔒 **Owner Only** — Your vault, your ETH, your rules
- ✅ **Auto Completion** — Goal marks complete when target hit
- 📡 **Onchain Events** — Every action emits blockchain event

---

## 📋 Contract Details

| Detail | Info |
|--------|------|
| **Network** | Base Mainnet |
| **Contract** | `0x62b2944f33eba8b438b49c098ed79e04b0840b09` |
| **Verified** | ✅ BaseScan |
| **Compiler** | Solidity 0.8.20 |
| **License** | MIT |
| **Live App** | [basevault-protocol.netlify.app](https://basevault-protocol.netlify.app) |
🔗 [View on BaseScan](https://basescan.org/address/0x62b2944f33eba8b438b49c098ed79e04b0840b09)

---

## 🛠️ Core Functions

```solidity
createGoal(name, targetAmount, deadlineDays)
deposit(goalId)
withdraw(goalId)
getGoal(goalId)
getAllGoals()
```

---

## 🗺️ Roadmap

- [x] Smart contract deployed & verified on Base
- [x] Frontend UI (in progress)
- [x] Mobile responsive design
- [x] Multiple wallet support
- [x] Goal sharing feature

---

## 👨‍💻 Builder

Built by [@Huzaifa_0101](https://twitter.com/Huzaifa_0101)  
Active on Base since Feb 2024 | 1900+ onchain transactions

## Security

- Smart contract deployed and verified on BaseScan
- No admin keys after deployment
- Non-custodial — only you control your funds
- Open source — MIT License
## Supported Assets

- ETH — Native Base token
- Deposit and withdraw anytime
- Non-custodial — your keys, your funds
- ## Why BaseVault

- Save ETH securely onchain
- No bank — no middleman
- Withdraw anytime
- Fully transparent on BaseScan
## How Funds Are Secured

- Smart contract holds funds
- Only your wallet can withdraw
- No admin access
- Auditable on BaseScan anytime
---

## 📄 License

MIT License — free to use and build upon.
