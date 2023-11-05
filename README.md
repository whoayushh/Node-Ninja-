# NODE NINJA REAL ESTATE APP

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

  ##INTRODUCTION
Node Ninja Estate is a smart contract platform built on the Ethereum blockchain that allows users to buy tokenised real estates with cryptocurrency. The aim is to use tokenisation and blockchain technology to remove the barriers of entry to investing posed by traditional financial institutions

## WORKING
- The buyer views properties of interest submits an offer to the seller and approves of property
- The buyer provides an earnest money deposit as a sign of good faith and commitment to the purchase. This deposit is held in escrow.
- Home inspection is done by inspector to evaluate the property
- The lender conducts underwriting, assessing the buyer's creditworthiness and confirming the property's eligibility for financing
- Lender typically pays lends in line loan amount
- Seller approves of all the above transactions and is ready to sell
- The seller then sells the property. The buyer receives ownership of the property, and the seller receives the proceeds from the sale.
  

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
