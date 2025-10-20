# Crypto Zombies Project

## Project Contributors
- Jayvardhan Gundeti (866796881)
- Anirudh Mukherjee (820963189)

## Key Features Implemented
1. Enhanced user interface design
2. Refactored starter code to remove hard-coded values
3. Enabled creation of multiple zombies from a single account
4. Added functionality to select specific zombies for leveling up
5. Added kitty smart contract to the backend.
6. Display unique images for each zombie generated from their DNA
7. Added functionality to transfer zombies from one account to another
8. Added functionality for the zombies to feed on ktties

## Project Information
Developed using the provided starter code template

**Demonstration Video:** https://youtu.be/dvyIc3VTk7Q?si=xxvrjXechqUeoed0

## Required Software
Ensure your local environment has the following installed:
- Truffle v5.11.5 (core: 5.11.5)
- Ganache v7.9.1
- Solidity v0.5.16 (solc-js)
- Node.js v16.17.0
- Web3.js v1.10.0
- MetaMask browser extension

## Installation & Setup Guide

1. Install project dependencies with `npm i`
2. Configure Ganache connection through the truffle-config.js file
3. Compile smart contracts using `truffle compile`
4. Deploy contracts to the network with `truffle migrate`
5. Open the MetaMask browser extension
6. Add the Ganache network to MetaMask using these parameters:
   - **Network Name:** Ganache
   - **RPC URL:** HTTP://127.0.0.1:7545
   - **Chain ID:** 1337
   - **Currency Symbol:** ETH
7. Import a Ganache account into MetaMask by copying a private key from the accounts section
8. Update the cryptoZombiesAddress variable in index.html with your deployed contract address from Ganache
9. Launch the development server with `npm start`