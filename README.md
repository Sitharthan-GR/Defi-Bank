# 💸 DeFi Bank
A decentralized finance (DeFi) banking application that allows users to deposit, withdraw, and earn interest on crypto assets using smart contracts. This project demonstrates the integration of blockchain, smart contracts, and a frontend interface.

# 🧱 Tech Stack
* React js
* Smart Contracts (Backend)
* Solidity – Smart contract development
* Hardhat – Ethereum development environment

* Ethers.js – Blockchain interaction

# 🔹 Frontend
React.js – UI framework

TailwindCSS – Styling

Web3Modal – Wallet connection (e.g., MetaMask)

# 🚀 Features
* Deposit ETH and earn interest

* Withdraw with real-time balance updates

* View interest accrued over time

* MetaMask integration for secure login

* Smart contract interactions via Ethers.js

# 🛠️ Setup Instructions
Clone the repository

```
git clone https://github.com/your-username/defi-bank.git
cd defi-bank
```
Install dependencies
```
npm install
cd frontend && npm install
```
Compile smart contracts
```
npx hardhat compile
```
Deploy contracts locally
```
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost

cd frontend
npm start
```
# 🧪 Testing
To run contract tests:
```
npx hardhat test
```


