# DAR-COIN (DAR)

![DAR-COIN Logo](https://raw.githubusercontent.com/kongali1720/Dar-Coin/main/DAR-COIN-logo.png)

DAR-COIN is a global ERC-20 utility token…

DAR-COIN (DAR) is a global ERC-20 utility token built on Ethereum.

## 🌍 Vision
To power transparent, decentralized, and secure digital finance solutions worldwide.

## 🔗 Network
Ethereum Mainnet

## 📊 Token Supply
100,000,000 DAR

## 📑 Token Standard
ERC-20

## 🚀 Features
- Transparent On-chain Transactions
- ICO Smart Contract
- Liquidity Lock Mechanism
- Future Staking System

## 📜 Contract (TBA)
Coming Soon

## 🌐 Website
Coming Soon

## ⚠ Disclaimer
DAR-COIN is a utility token. It does not represent ownership, shares, or guaranteed profits.

🪙 CONTRACT DARCoin.sol (Basic ERC20)
```bash
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract DARCoin is ERC20, Ownable {

    uint256 public constant MAX_SUPPLY = 100000000 * 10 ** 18;

    constructor() ERC20("DAR-COIN", "DAR") {
        _mint(msg.sender, MAX_SUPPLY);
    }
}
```




