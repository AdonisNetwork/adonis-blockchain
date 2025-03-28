# 🦠 Adonis Edge

Adonis Edge is an open-source, high-performance, Ethereum-compatible blockchain framework built by **Adonis Network**.\
This project empowers developers and businesses to launch their own secure, scalable, and customizable blockchain networks with integrated smart contract support.

## 🚀 Key Features

- **Ethereum-Compatible**: Fully supports EVM & Solidity smart contracts.
- **High Performance**: Designed for fast finality and low transaction fees.
- **Modular Architecture**: Easy to extend, modify, and deploy.
- **Custom Token Support**: Projects can easily create their own ERC20 / ERC721 tokens.
- **Validator & Governance**: Supports Proof-of-Stake validators and governance modules.

## 📄 License

This project is licensed under the **MIT License**\
Developed & Maintained by **Serkan Kaplan | Adonis Network**

## 📂 Project Structure

```
🔗 blockchain        -> Core blockchain logic
🔗 consensus         -> Consensus algorithm modules
🔗 contracts         -> Smart contract deployment and interfaces
🔗 core-contracts    -> Predeployed system contracts
🔗 crypto            -> Cryptographic libraries
🔗 forkmanager      -> Fork & Upgrade management
🔗 jsonrpc           -> JSON-RPC API layer
🔗 network           -> P2P Networking layer
🔗 state             -> State management
🔗 txpool            -> Transaction pool
🔗 validators        -> Validator set management
🔗 versioning        -> Version control and upgrades
🔗 docs              -> Documentation
```

## 🔥 Quick Start

```bash
git clone https://github.com/AdonisNetwork/adonis-edge.git
cd adonis-edge
make build
```

To run a local network:

```bash
./bin/adonis-edge server --config ./config/genesis.json
```

## 🧹 Roadmap

-

