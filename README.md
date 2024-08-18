# swisstronik-private-erc721

This project sets up a Hardhat environment to deploy and interact with an ERC-721 (NFT) contract and makes it private, on the Swisstronik testnet. Follow the steps below to get started.

## Prerequisites

Ensure you have the following installed:
- Node.js
- npm

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/web3bustler/swisstronik-private-erc721.git
    cd swisstronik-private-erc721
    ```

2. Make the setup script executable and run it:
    ```sh
    chmod +x private.sh
    ./private.sh
    ```

3. Follow the prompts to enter your private key and NFT details.

## Deployment

The script will:
- Install necessary dependencies.
- Create a Hardhat project.
- Configure the Hardhat environment.
- Create and compile an ERC-721 contract, and its private.
- Deploy the contract to the Swisstronik testnet.
- Mint an NFT using the deployed contract.

## Notes

- The contract address will be saved in `contract.txt`.
- The transaction hash for the minting process will be printed in the terminal.
