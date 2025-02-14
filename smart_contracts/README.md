# AI Mecha Wars - Smart Contracts

## Overview
This folder contains the **blockchain smart contracts** used for AI Mecha Wars, including token issuance, NFT-based assets, and staking mechanisms.

## Files
- `AI_Mecha_Token.sol` - ERC-20 token contract for $MECHA.
- `NFT_Mecha.sol` - ERC-721 NFT contract for AI-driven mecha units.
- `Staking.sol` - Smart contract for staking and in-game rewards.
- `/audits/` - Security audit reports.
- `/tests/` - Unit tests for contract validation.
- `/deployment/` - Deployment scripts for deploying contracts to the blockchain.

## How to Deploy
```bash
# Compile smart contracts
npx hardhat compile

# Run smart contract tests
npx hardhat test

# Deploy to testnet
npx hardhat run scripts/deploy.js --network testnet
