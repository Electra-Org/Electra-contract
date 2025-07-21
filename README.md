# 🗳️ Electra Voting Contract

This is the **smart contract backend** for the **Electra** project — a decentralized voting system built with **Solidity** and managed using **Hardhat**.

---

## ✨ Features

- ✅ Create proposals on deployment  
- ✅ Users can vote only once  
- ✅ Vote counts stored securely on-chain  
- ✅ Ready for local development and testnet deployment  
- ✅ Easy integration with React frontend (via `ethers.js`)

---

## 📦 Tech Stack

| Tool | Purpose |
|------|---------|
| **Solidity** | Smart contract language |
| **Hardhat** | Ethereum development environment |
| **Ethers.js** | Deployment & contract interaction |
| **Mocha/Chai** | Testing framework |

---

## 🚀 Getting Started

### 1️⃣ Prerequisites

- [Node.js](https://nodejs.org/) >= 18
- npm or yarn
- A wallet like MetaMask (for testnet deployments)

---

### 2️⃣ Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/electra-contracts.git
cd electra-contracts
npm install

---

### 3️⃣ Project Structure
bash
Copy
Edit
electra-contracts/
 ├─ contracts/        
 │   └─ Voting.sol
 ├─ scripts/          
 │   └─ deploy.js
 ├─ test/            
 │   └─ Voting.js
 ├─ artifacts/        
 ├─ hardhat.config.js
 └─ package.json

 ---

### 4️⃣ Compile Contracts
bash
Copy
Edit
npx hardhat compile

5️⃣ Run a Local Network
Start a local Hardhat Ethereum node:

bash
Copy
Edit
npx hardhat node

6️⃣ Deploy Locally
Open another terminal and run:

bash
Copy
Edit
npx hardhat run scripts/deploy.js --network localhost
Output will show the deployed contract address:

css
Copy
Edit
Voting deployed to: 0x1234...abcd


7️⃣ Test the Contract
Run unit tests:

bash
Copy
Edit
npx hardhat test
Expected output:

csharp
Copy
Edit
  Voting
    ✔ Should deploy with proposals
    ✔ Should allow voting and track counts