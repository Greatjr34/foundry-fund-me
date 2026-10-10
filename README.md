# FundMe

A simple crowdfunding contract built with Foundry while learning smart contract development on Cyfrin Updraft.

## What it does

- Anyone can fund the contract with ETH
- A minimum funding amount in USD is enforced using a Chainlink ETH/USD price feed
- Only the owner can withdraw the funds

## Deployed (Sepolia)

[0xeAA0D79A3B57D97DccB44a3858c568D125CeB7c4](https://sepolia.etherscan.io/address/0xeAA0D79A3B57D97DccB44a3858c568D125CeB7c4#code)

## Getting started

```bash
git clone --recurse-submodules https://github.com/Greatjr34/foundry-fund-me.git
cd foundry-fund-me
forge build
forge test
```

## Deploy

Create a `.env` file with `SEPOLIA_RPC_URL`, `SEPOLIA_PRIVATE_KEY` and `ETHERSCAN_API_KEY`, then:

```bash
make deploy-sepolia
```

## Built with

Solidity, Foundry, Chainlink price feeds