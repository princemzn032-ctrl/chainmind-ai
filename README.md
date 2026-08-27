# ChainMind AI

*Decentralized Intelligence for Smarter Decisions*

ChainMind AI is a fully functional, production-ready decentralized application (dApp) that combines Artificial Intelligence, Blockchain, Web3, and Decentralized Storage into one platform.

## 🚀 Overview

ChainMind AI provides an ecosystem where users can securely interact with intelligent AI services while blockchain ensures transparency, security, decentralization, and immutable records.

## 🌟 Key Features

- **AI Intelligence Engine:** Predictive analytics, smart recommendations, fraud/risk detection, and intelligent decision support.
- **Blockchain & Smart Contract Layer:** Polygon support, smart contracts for DAO voting, and on-chain verification.
- **AI-Powered DAO Governance:** Create proposals, vote securely, and receive AI-driven proposal analysis and risk detection.
- **AI Fraud & Risk Detection:** Real-time dashboards displaying suspicious activity, risk scores, and AI confidence levels.
- **Predictive Analytics:** Visual dashboards forecasting growth, network activity, and transaction trends.
- **Decentralized Storage:** IPFS-based document and dataset storage for secure and decentralized access.
- **Web3 Wallet Integration:** Seamless connection with MetaMask and WalletConnect.

## 🛠️ Technology Stack

- **Frontend:** Next.js, Tailwind CSS, Framer Motion, Recharts
- **Backend:** Node.js, Express.js
- **Blockchain:** Solidity, Hardhat, Ethers.js, Polygon Amoy Testnet
- **Database:** MongoDB
- **AI Integration:** Abstraction layer supporting NLP, predictions, and fraud detection models
- **Storage:** IPFS via Pinata

## 🏗️ Project Architecture

```
User
   ↓
Frontend Application (Next.js)
   ↓
AI Intelligence Layer
   ↓
Backend API Layer (Node.js/Express)
   ↓
Blockchain Smart Contracts (Solidity)
   ↓
Ethereum / Polygon Network
        ↘
        IPFS Storage
```

## 💻 Local Development

### 1. Clone the repository

```bash
git clone <repository-url>
cd chainmind-ai
```

### 2. Install Dependencies

You'll need to install dependencies in each of the main directories:

```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install

# Blockchain
cd ../blockchain
npm install
```

### 3. Environment Variables

Create a `.env` file in the root of the project or in each respective folder (frontend, backend, blockchain) based on the provided `.env.example`.

### 4. Run the application

Start the frontend and backend servers:

```bash
# In frontend terminal
npm run dev

# In backend terminal
npm run dev
```

## 🚀 Deployment

- **Frontend:** Deploy to Vercel.
- **Backend:** Deploy to Render or Railway.
- **Database:** Use MongoDB Atlas.
- **Contracts:** Deploy to Polygon Amoy Testnet using Hardhat.

## 🧪 Demo Mode

The application includes a fully functional **Demo Mode** for hackathon judges to explore the platform without needing to connect a wallet or use real funds/API keys. Simulated AI predictions, fraud detection data, and DAO proposals are included.
