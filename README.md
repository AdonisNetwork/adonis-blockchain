# 🦠 Adonis Edge

**Adonis Edge** is a high-performance, open-source, Ethereum-compatible blockchain framework developed by [Adonis Network](https://adonis.network).  
It empowers developers and enterprises to deploy secure, scalable, and customizable blockchain networks with integrated smart contract support.

---

## 🚀 Key Features

✅ **Ethereum Compatibility** — Full EVM support with Solidity smart contracts  
✅ **High Performance** — Fast finality, low fees, optimized transaction throughput  
✅ **Modular Architecture** — Clean, scalable, and extensible structure  
✅ **Custom Token Standards** — Easy creation of ERC-20, ERC-721 tokens  
✅ **Validator & Governance Modules** — Built-in Proof-of-Stake validator support and governance mechanism  

---

## 📂 Project Structure

```
📁 blockchain        → Core blockchain logic
📁 consensus         → Consensus algorithm modules
📁 contracts         → Smart contract deployment & interfaces
📁 core-contracts    → System contracts predeployed
📁 crypto            → Cryptographic utilities
📁 forkmanager      → Fork & upgrade management
📁 jsonrpc           → JSON-RPC API layer
📁 network           → P2P Networking
📁 state             → State management layer
📁 txpool            → Transaction pool
📁 validators        → Validator set & staking
📁 versioning        → Version control & network upgrades
📁 docs              → Documentation
```

---

## ⚙️ Quick Start

Clone the repository and build:

```bash
git clone https://github.com/AdonisNetwork/adonis-edge.git
cd adonis-edge
make build
```

Run a local blockchain node:

```bash
./bin/adonis-edge server --config ./config/genesis.json
```

---

## 🧭 Roadmap

- [x] Blockchain Node Setup
- [x] Smart Contract Module Integration
- [x] Transaction Pool Implementation
- [x] Consensus Mechanism Configuration
- [x] JSON-RPC API Integration
- [x] Genesis Configuration
- [x] Validator Management Module
- [x] Gas Price Oracle Implementation
- [x] Documentation & Developer Guide
- [ ] Advanced Governance Module
- [ ] Automated Reward Distribution
- [ ] Cross-Chain Bridge (Future Release)

---

## 🤝 Contributor Guide

We welcome contributions from the community! Here’s how you can help:

### 🧩 How to Contribute

1. **Fork the Repository**
2. **Create a Feature Branch**
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Commit Your Changes**
    ```bash
    git commit -m "Add: Description of your changes"
    ```
4. **Push to Your Forked Repository**
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a Pull Request**
    - Explain what you’ve done.
    - Link to any related issue.

### 🎯 Contribution Rules

- Write clean, maintainable code.
- Follow existing project structure and naming conventions.
- Add comments where necessary.
- Submit one feature/fix per pull request.
- Ensure all tests pass before submitting.

### 🗂️ Useful Commands

```bash
make build         # Build the project
make test          # Run tests
make lint          # Lint the codebase
```

---

## 📄 License

Licensed under the **MIT License**  
Developed & Maintained by **[Serkan Kaplan](https://serkankaplan.adonis.network) | [Adonis Network](https://adonis.network)**
