🔗 Supply Chain Blockchain DApp
📦 Supply Chain Management using Blockchain Technology

A decentralized application (DApp) designed to ensure transparency, security, and traceability in supply chain management by leveraging Ethereum blockchain and smart contracts.

🎯 Project Overview

This project implements a blockchain-based supply chain management system that allows tracking a product from raw material sourcing to final sale.
All operations are recorded on the blockchain, ensuring immutability, trust, and elimination of intermediaries.

The application is built as part of the Blockchain module, with a strong focus on conceptual understanding, smart contract design, and Web3 integration.

✅ Key Benefits

🔍 Transparency: Every step of the supply chain is recorded on-chain

🔐 Security: Blockchain immutability prevents data tampering

🧾 Traceability: Full product lifecycle tracking

⚙️ Automation: Smart contracts replace manual processes

🌍 Decentralization: No central authority required

✨ Features

🔐 Role-Based Access Control

Owner (Administrator)

Raw Material Supplier

Manufacturer

Distributor

Retailer

📦 Product Lifecycle Management

Order creation

Raw material supply

Manufacturing

Distribution

Retail

Sold

📊 Real-Time Product Tracking

🔗 MetaMask Wallet Integration

🎨 Modern UI with Next.js & Tailwind CSS

📱 Responsive Web Interface

🛠 Technology Stack
🔗 Blockchain & Backend

Ethereum

Solidity

Hardhat

Ganache

MetaMask

🎨 Frontend

Next.js

TypeScript

Tailwind CSS

Web3.js

⚙️ Tools

Node.js

npm / yarn

Git & GitHub

Visual Studio Code

🏗 System Architecture

The application follows a decentralized architecture:

User → Next.js Frontend → Web3.js → MetaMask → Ganache → Smart Contract


Smart contracts manage business logic and data

Frontend interacts with blockchain via Web3.js

MetaMask handles authentication and transaction signing

Ganache simulates a local Ethereum network

🔄 Supply Chain Flow
Order → Raw Material Supply → Manufacturing → Distribution → Retail → Sold


Each step is validated by a specific role and recorded on the blockchain.

📦 Project Structure
Supply-Chain-Blockchain/
│
├── backend/
│   ├── contracts/
│   │   └── SupplyChain.sol
│   ├── scripts/
│   │   └── deploy.ts
│   ├── hardhat.config.ts
│
├── client/
│   ├── src/
│   ├── public/
│   └── next.config.js
│
└── README.md

🚀 Installation & Setup
Prerequisites

Node.js (v18+)

Git

Ganache

MetaMask (Browser Extension)

1️⃣ Clone the Repository
git clone https://github.com/LamiaeAndof/Supply-chain-Blockchain.git
cd Supply-chain-Blockchain

2️⃣ Install Dependencies

Backend

cd backend
npm install


Frontend

cd ../client
npm install

3️⃣ Configure Ganache

Start Ganache

Note RPC URL (e.g. http://127.0.0.1:7545)

Note Chain ID (e.g. 1337)

4️⃣ Deploy Smart Contract
cd backend
npx hardhat compile
npx hardhat run scripts/deploy.ts --network ganache

5️⃣ Configure MetaMask

Add Ganache network

Import an account from Ganache using private key

6️⃣ Run the Frontend
cd client
npm run dev


➡️ Application runs on:
http://localhost:3000

📖 Usage Guide
🔹 Register Roles

Only the Owner can register:

Raw Material Suppliers

Manufacturers

Distributors

Retailers

Each role is linked to an Ethereum address.

🔹 Create Product Order

Product name

Product description

Unique ID

🔹 Supply Chain Processing

Each role performs its action:

Supplier → Supply

Manufacturer → Manufacture

Distributor → Distribute

Retailer → Sell

🔹 Track Product

Enter Product ID

View full lifecycle

Verify blockchain data

🔐 Smart Contract Overview

Main contract: SupplyChain.sol

Roles Management

addRMS()

addManufacturer()

addDistributor()

addRetailer()

Product Flow

addMedicine()

RMSsupply()

Manufacturing()

Distribute()

Retail()

sold()

showStage()

👥 Project Team

Prepared by:

Lamiae Andof

Manal Ferza

Yassine Chmirrou

Zakaria Tibtiba

Supervised by:
Pr. Sassi Imad

📄 License

This project is licensed under the MIT License.

⭐ Final Note

This project demonstrates how blockchain technology can be applied to real-world systems such as supply chain management, offering trust, automation, and transparency.
