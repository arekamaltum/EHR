# 🏥 Decentralized Electronic Health Record (EHR) System

A secure blockchain-powered Electronic Health Record (EHR) platform built using React, Node.js, Ethereum smart contracts, IPFS/Filecoin storage, and MetaMask wallet authentication.

This platform enables patients and doctors to securely manage and share medical records using decentralized technologies and cryptographic access control.

---

# 🚀 Features

## 👤 Patient Features
- MetaMask wallet authentication
- Secure registration using Ethereum wallet signatures
- Upload encrypted medical records
- View medical history
- Manage access permissions
- Approve / revoke doctor access
- Secure decentralized file storage

---

## 🩺 Doctor Features
- MetaMask login
- Request patient record access
- View granted patient records
- Access encrypted EHR data
- Manage patient consultations

---

## 🔐 Security Features
- JWT Authentication
- Ethereum signature verification
- AES-256 encryption
- RSA key-pair support
- Proxy Re-Encryption (PRE)
- Blockchain-based access control

---

## ⛓ Blockchain Features
- Smart contracts using Solidity
- Hardhat local blockchain support
- Sepolia testnet support
- On-chain permission management

---

## 📦 Storage Features
- IPFS/Filecoin integration
- Encrypted decentralized medical records
- Secure document uploads

---

# 🛠 Tech Stack

## Frontend
- React
- TypeScript
- Vite
- Axios
- Tailwind CSS
- Ethers.js

---

## Backend
- Node.js
- Express.js
- JWT
- Multer
- CORS
- Helmet
- Morgan

---

## Blockchain
- Solidity
- Hardhat
- Ethers.js
- MetaMask

---

## Storage
- IPFS
- Web3.Storage

---

# 📁 Project Structure

```bash
major-project/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── utils/
│   │   └── server.js
│   │
│   ├── contracts/
│   ├── scripts/
│   ├── hardhat.config.cjs
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── services/
│   │   └── config/
│   │
│   ├── public/
│   ├── vite.config.ts
│   └── package.json
│
└── README.md
