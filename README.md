# Nft-marketplace

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ipfs](https://ipfs.io/) (Metadata storage)
- [React routers](https://v5.reactrouter.com/) (Navigational components)

- ## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)
- Install [Hardhat](https://hardhat.org/)

- ## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
cd Nft-marketplace
npm install
```
### 3. Boot up local development blockchain
```
cd Nft-marketplace
npx hardhat node
```

### 4. Connect development blockchain accounts to Metamask

### 5. Migrate Smart Contracts
`npx hardhat run src/backend/scripts/deploy.js --network localhost`

### 6. Run Tests
`npx hardhat test`

### 7. Launch Frontend
`npm run start`
