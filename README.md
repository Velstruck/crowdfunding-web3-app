
# CROWDFUNDING APP USING Web3   

This project aims to create a secure and user-friendly crowdfunding platform leveraging the power of Web3 and blockchain technology.


## Key Features

- Create Campaigns
- View all campaings
- Crypto Donations
- Blockchain Security



## Tech Stack

NextJS, Tailwind CSS, Solidity (Smart Contracts), Hardhat (Dummy ETH), NodeJS

## Installation

Install dependencies

```bash
  npm install 
  cd crowdfunding
```
Open 2 terminals for hardhat and deploying smart contracts

In terminal 1:
```bash
  npx hardhat node
```
(Select any of the dummy accounts for ETH, same should be imported in MetaMask Wallet through **private key**)

In terminal 2:
```bash
  npx hardhat run --network localhost scripts/deploy.js
```
(Now copy the JSON generated in artifacts/contracts to crowdfunding/Context)

After that create a localhost server for MetaMask with following config:

```
Network name : localhost
New RPC URL: http://localhost:8545
Chain ID: 31337
Currency symbol: ETH
```
In terminal 2:
```bash
  npm run dev
```
Connect the wallet and Enjoy!!🎉
    
