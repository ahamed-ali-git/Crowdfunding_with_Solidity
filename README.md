# Crowdfunding DApp

A decentralized crowdfunding platform powered by Thirdweb, Hardhat, and Ethereum, enabling secure and transparent campaign creation and contribution management.

## Overview

This decentralized application (DApp) leverages blockchain technology to create a trustless crowdfunding platform where campaign creators can raise funds and contributors can participate with complete transparency and security.

## Features

* Campaign Management
  - Create campaigns with customizable funding goals
  - Set campaign duration and end dates
  - Detailed campaign information storage
  - Campaign image upload support

* Financial Operations
  - Secure multi-user contribution system
  - Direct fund ownership for campaign creators
  - Transparent transaction recording
  - Blockchain-based fund management

* Security & Transparency
  - Immutable transaction records
  - Smart contract-based security
  - Decentralized fund management
  - Full transaction history

## Prerequisites

* Node.js v16 or later
* Hardhat development framework
* Metamask or compatible Ethereum wallet
* Thirdweb CLI tools

## Installation

1. Clone the repository:
   bash
   git clone (https://github.com/ahamed-ali-git/Crowdfunding_with_Solidity.git)
   cd project_crowdfunding/web3
   

2. Install dependencies:
   bash
   npm install


## Configuration

1. Create a `.env` file in the web3 directory with the following variables:
   
   THIRDWEB_SECRET_KEY=your-secret-key
   ALCHEMY_API_URL=https://eth-mainnet.alchemyapi.io/v2/your-alchemy-key
   PRIVATE_KEY=your-wallet-private-key


2. Configure each environment variable:
   * `THIRDWEB_SECRET_KEY`: Your Thirdweb API authentication key
   * `ALCHEMY_API_URL`: Alchemy API endpoint for Ethereum network access
   * `PRIVATE_KEY`: Ethereum wallet private key for contract deployment

## Deployment

1. Deploy smart contracts:
   bash
   npx thirdweb@latest deploy -k $THIRDWEB_SECRET_KEY

2. Launch the application:
   bash
   npm run dev
   

## Usage Guide

### Creating a Campaign

1. Access the campaign creation interface
2. Specify campaign parameters:
   * Funding goal amount
   * Campaign end date
   * Detailed description
   * Campaign imagery
3. Submit for blockchain deployment

### Contributing to Campaigns

1. Browse available campaigns
2. Connect your Ethereum wallet
3. Select contribution amount
4. Confirm transaction through wallet

## Architecture

### Technical Stack

* Frontend Framework: React.js
* Backend Runtime: Node.js
* Blockchain Development: Hardhat, Thirdweb
* Smart Contract Language: Solidity
* Decentralized Storage: IPFS (via Thirdweb)

## Troubleshooting

### Common Issues

1. Secret Key Configuration
   * Error: "Please include the -k flag with your secret key"
   * Solution: Verify .env configuration or provide key directly

2. Transaction Delays
   * Error: "Transaction is taking too long"
   * Solutions:
     - Check network connectivity
     - Verify wallet configuration
     - Confirm network selection

### Additional Resources

* [Thirdweb Documentation](https://portal.thirdweb.com/docs)
* [Hardhat Guides](https://hardhat.org/guides)
* [Ethereum Development Documentation](https://ethereum.org/developers)

## Contributing

We welcome contributions to improve the platform:

1. Fork the repository
2. Create a feature branch
3. Implement improvements
4. Submit a pull request

Please follow our coding standards and include appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE] file for complete details.
