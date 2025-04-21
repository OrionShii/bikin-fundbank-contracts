# 🏦 FundBank Contracts

A simple Ethereum smart contract project for securely depositing and withdrawing Ether. Built for educational and prototype-level use in Web3 environments.

---

## 🚀 Features

- 🔐 **Deposit Ether** with strict value checks
- 💸 **Withdraw Ether** with safe transfer logic
- 📊 **Check Balances** per user
- ⚠️ Custom errors for clean & efficient error handling
- 📢 Emits events for deposits and withdrawals

---

## 🛠️ Stack

- [Solidity ^0.8.25](https://soliditylang.org/)
- [Foundry](https://book.getfoundry.sh/) (cast, forge)
- Local Anvil / Hardhat for RPC testing

---

## 📁 Contract Overview

```solidity
function deposit(uint256 amount) public payable;
function withdraw(uint256 amount) public;
function checkBalance(address user) public view returns (uint256);
```
## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
