# ethCord

## Problem Statement:

In traditional messaging platforms, user engagement and contribution often lack direct incentives beyond social interaction. Additionally, centralized systems control user data and access, leading to concerns regarding privacy and censorship. These limitations necessitate a solution that incentivizes user participation while ensuring decentralized control and privacy. Also, people tend to spam with fraudulent links, scamming people.

## Solution:
Blockchain technology offers a promising solution to address the shortcomings of traditional messaging platforms. By leveraging blockchain, we can create a decentralized messaging platform that incentivizes user engagement, ensures data privacy, and empowers users with ownership and control over their interactions.


## Key Features:
- Incentivized Participation: Users are required to pay a nominal fee in Ethereum (ETH) to access specific channels within the messaging platform. This fee serves as an incentive for meaningful engagement and contributions.
- NFT Minting: Upon payment, the platform automatically mints a non-fungible token (NFT) representing the user's access rights to the channel.
- Decentralized Access Control: Utilizing blockchain technology ensures decentralized control over channel access. There is no central authority controlling access, and users maintain ownership and control over their data and interactions.
- Privacy and Security: The platform prioritizes user privacy and security by leveraging blockchain's inherent encryption and decentralization features. Encrypted communication ensures data privacy, while decentralization mitigates risks associated with centralized platforms, such as data breaches and surveillance.
- Immutable Records: All transactions, including channel access payments and NFT minting, are recorded on the blockchain. These records are transparent, immutable, and publicly accessible, providing transparency, accountability, and assurance.

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [Socket.io](https://socket.io/) (Client & Server communication)

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

### 6. Start Socket.io server
`$ node server.js`

### 7. Start frontend
In a separate terminal execute:
`$ npm run start`
