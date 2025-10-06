# DataRoots - Decentralized Data Sha- **Currency Symbol**: U2U
- **Decimals**: 18
- **Block Explorer URL**: https://u2uscan.xyzg Platform

DataRoots is a blockchain-based platform that enables secure, decentralized sharing of data with fine-grained access control. Users can upload their data to IPFS, register it on the blockchain, and grant or revoke access to other users.

## Features

- **Decentralized Storage**: All data is stored on IPFS, ensuring censorship resistance and availability
- **Blockchain-Based Access Control**: Smart contracts manage access permissions
- **Custom Data Names**: Users can name their data for easy identification
- **Data Categories**: Organize data by categories (Personal, Educational)
- **Time-Limited Access**: Grant access for specific time periods
- **Refund Mechanism**: Partial refunds when access is revoked before expiration
- **Data Deactivation**: Ability to remove data from the platform

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Blockchain**: U2U Solaris Mainnet
- **Smart Contracts**: Solidity
- **Storage**: IPFS via Pinata
- **Web3 Integration**: ethers.js

## Getting Started

### Prerequisites

- MetaMask or another Ethereum wallet
- Access to U2U Solaris Mainnet network

### U2U Solaris Mainnet Network Details

To connect to the U2U Solaris Mainnet network, add the following configuration to your MetaMask:

- **Network Name**: U2U Solaris Mainnet
- **RPC URL**: https://rpc-mainnet.u2u.xyz
- **Chain ID**: 39 (0x27 in hex)
- **Currency Symbol**: U2U
- **Decimals**: 18
- **Block Explorer URL**: https://explorer.open-campus-codex.gelato.digital

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/dataroots.git
   cd dataroots
   ```

2. Install dependencies (if using a package manager):
   ```
   npm install
   ```

3. Configure your Pinata API keys in `app.js`:
   ```javascript
   const PINATA_API_KEY = 'your-api-key';
   const PINATA_API_SECRET = 'your-api-secret';
   const PINATA_JWT = 'your-jwt-token';
   ```

4. Deploy the smart contract to the U2U Solaris Mainnet network and update the contract address in `app.js`:
   ```javascript
   const contractAddress = "your-contract-address";
   ```

5. Open `index.html` in your browser or serve it using a local server.

### Connecting to U2U Solaris Mainnet

When you connect your wallet through the application, it will automatically attempt to:

1. Detect if you're connected to U2U Solaris Mainnet
2. Switch to U2U Solaris Mainnet if you're on a different network
3. Add U2U Solaris Mainnet to your wallet if it's not already configured

If you don't have MetaMask installed, the application will attempt to connect directly to the U2U Chain RPC URL, but functionality will be limited.

