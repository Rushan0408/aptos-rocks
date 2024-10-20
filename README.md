# Rock, Paper, Scissors Game DApp

This decentralized application (DApp) allows users to play the classic game of Rock, Paper, Scissors on the Aptos blockchain. The game logic and smart contract are implemented in Move, with a user-friendly interface built using **TypeScript.

## Features
- Interactive Gameplay: Play Rock, Paper, Scissors against other users.
- On-Chain Logic: All game outcomes are processed on the Aptos blockchain.
- Move Smart Contract: Game mechanics are securely handled via Move language.
- Simple UI: A clean, responsive interface to select rock, paper, or scissors, and view results.

## Technologies Used
- Move Language: For writing the game logic and handling game outcomes on-chain.
- Aptos Blockchain: Provides secure and decentralized infrastructure for the game.
- TypeScript: Used for building the front-end and interacting with the Aptos blockchain.

## How It Works
1. Select Your Move: Players choose between Rock, Paper, or Scissors.
2. Submit Move: After selecting a move, the user clicks the "Submit" button.
3. Blockchain Validation: The Move smart contract evaluates the outcome based on the opponent’s move.
4. Results: The winner is determined and displayed on the front-end, with the result securely recorded on the blockchain.

## Prerequisites
- Aptos CLI: Required to deploy and interact with the smart contracts.
- Move SDK: For writing and managing the smart contracts.
- Node.js & npm: For running the TypeScript front-end.

## Deploy the Smart Contract
To deploy the smart contract:

Install Aptos CLI.

Update the Move.toml file with your wallet address:

aptos init
Add your Account addr here for Deployment
primitives = "0x6d0177e989c24a754898079abcda70faca206529a4101072dfa54b91d17727b5"
Compile and publish the contract:

aptos move compile
aptos move publish
