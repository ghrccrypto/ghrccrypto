## Hi there 👋

<!--
**ghrccrypto/ghrccrypto** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# 🌍 GHRCrypto (Giving Homeless Relief Coin)

**GHRCrypto (GHRC)** is a community-driven cryptocurrency designed to help fight homelessness.  
Every transaction automatically contributes a small percentage to a **charity wallet**, which supports food programs, shelters, and long-term housing solutions.

---

## ✨ Mission
Our mission is simple:
- Use blockchain transparency to ensure donations are visible and trackable.
- Empower communities to contribute to real-world impact.
- Partner with verified charities to maximize reach and effectiveness.

---

## ⚙️ How It Works
- **Token standard**: ERC-20 (Ethereum-compatible, works on Polygon, BSC, etc.)
- **Charity Fee**: A percentage of every transaction (default 1%) is automatically sent to the charity wallet.
- **Fee Exemptions**: Certain addresses (charity wallet, owner, exchanges) can be exempt from fees.
- **Supply**: Example setup → 1 billion GHRC tokens at launch.

---

## 🛠️ Tech Overview
- Written in **Solidity**
- Based on **OpenZeppelin** contracts for security
- Includes:
  - Burnable tokens
  - Pausable transfers
  - Owner-controlled charity settings
  - Transparent fee logic

---

## 📦 Deployment (for developers)
1. Install dependencies:
   ```bash
   npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
   npm install @openzeppelin/contracts
