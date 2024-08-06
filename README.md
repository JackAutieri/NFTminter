# NFT Minter 1.0

This project is a decentralized application (dApp) that allows users to mint their own NFTs (Non-Fungible Tokens) on the Ethereum blockchain. It utilizes the Alchemy Web3 library for blockchain interactions, MetaMask for wallet integration, and Pinata for IPFS storage of metadata.

## Features

- **Connect Wallet**: Connect your Ethereum wallet using MetaMask.
- **Mint NFTs**: Mint NFTs by uploading an image, providing a name, and adding a description.
- **View Status**: Display the transaction status and links to view minted NFTs on Etherscan.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MetaMask](https://metamask.io/) (installed as a browser extension)
- [Alchemy](https://www.alchemy.com/) API Key
- [Pinata](https://www.pinata.cloud/) API Key and Secret

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/nft-minter.git
   cd nft-minter/minter-starter-files
   ```

2. **Install dependencies:**

   ```bash
   yarn install
   # or
   npm install
   ```

3. **Create a `.env` file:**

   Create a `.env` file in the root directory and add your API keys:

   ```
   REACT_APP_ALCHEMY_KEY=your-alchemy-key
   REACT_APP_PINATA_KEY=your-pinata-key
   REACT_APP_PINATA_SECRET=your-pinata-secret
   ```

### Usage

1. **Start the application:**

   ```bash
   yarn start
   # or
   npm start
   ```

2. **Open the application in your browser:**

   Navigate to `http://localhost:3000` in your web browser.

3. **Connect MetaMask:**

   Click on the "Connect Wallet" button to connect your MetaMask wallet.

4. **Mint an NFT:**

   - Enter the link to the asset (image URL).
   - Provide a name for your NFT.
   - Add a description.
   - Click the "Mint NFT" button.

### Code Overview

- **`App.js`**: Main component wrapping the application with `ChakraProvider` and `UserProvider`.
- **`Minter.js`**: Contains the logic for connecting the wallet, minting NFTs, and interacting with the smart contract.
- **`utils/interact.js`**: Utility functions for interacting with MetaMask and the Ethereum blockchain.

### Styles

The application uses basic styles defined in `index.css`. The logo animation is controlled via the `App-logo-spin` keyframes.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgements

- [Alchemy](https://www.alchemy.com/)
- [Pinata](https://www.pinata.cloud/)
- [MetaMask](https://metamask.io/)


# 🗃 NFT Minter Tutorial Starter Files
This project contains the starter files for [Alchemy's NFT Minter tutorial](https://docs.alchemyapi.io/alchemy/tutorials/nft-minter), in which we teach you how to connect your smart contract to your React dApp project by building an NFT Minter using Metamask and Web3.
