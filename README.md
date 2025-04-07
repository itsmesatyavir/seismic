# Seismic Auto Bot

A Node.js tool for deploying ERC-20 compatible tokens on the **Seismic devnet** and automating token transfers to random addresses — ideal for testing and airdrop simulations.

## Features

- One-click token deployment on Seismic devnet
- Automated token transfers to random addresses
- Real-time transaction status updates
- Simple interactive CLI

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A funded wallet (with ETH on Seismic devnet)

## Installation

```bash
# Clone the repository
git clone https://github.com/itsmesatyavir/seismic.git

# Navigate to the project directory
cd seismic

# Install dependencies
npm install
```

## Configuration

Create a `.env` file in the root directory and add your wallet’s private key:

```
PRIVATE_KEY=your_private_key_here
```

> ⚠️ **Security Warning:** Never commit your `.env` file or share your private key publicly.

## Usage

Start the bot with:

```bash
npm start
```

You'll be guided through:

1. Creating a token (name, symbol, total supply)
2. Deploying it to the Seismic devnet
3. Optionally sending tokens to random addresses

## Token Contract Features

- Standard ERC-20 functionality
- Name, symbol, and total supply input
- Transfer and balance tracking
- Approval and allowance logic
- Emits standard ERC-20 events

## Seismic Devnet Details

- **Network:** Seismic devnet  
- **Chain ID:** 5124  
- **RPC URL:** https://node-2.seismicdev.net/rpc  
- **Explorer:** https://explorer-2.seismicdev.net/

## License

This project is licensed under the MIT License.

## Support

For questions or issues, open an [issue here](https://github.com/itsmesatyavir/seismic/issues).
