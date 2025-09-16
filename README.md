# FundMe

A crowdfunding smart contract written in Solidity.  
The contract allows users to send ETH, while only the contract owner can withdraw the collected funds.  
Each contributor’s amount is tracked, and a minimum funding threshold is enforced using Chainlink Price Feeds (ETH → USD).

---

## 🚀 Features

- **Funding**: Anyone can call `fund` to contribute ETH.  
- **Tracking contributions**: Each address’s total contribution is stored.  
- **Withdrawal**: Only the contract owner can withdraw all the funds via `withdraw`.  
- **Minimum threshold**: Ensures each contribution meets a minimum USD value.  

---

## 🛠️ Tech Stack

- [Solidity ^0.8.18](https://soliditylang.org/)  
- [Foundry](https://book.getfoundry.sh/) — testing and deployment  
- [Chainlink Price Feeds](https://docs.chain.link/data-feeds) — ETH/USD conversion  

---



