# Lottery Smart Contract

This is a simple smart contract written in Solidity for a lottery game. The contract is designed to be deployed on the Ethereum blockchain and allows players to enter the lottery by sending Ether to the contract address. The winner is chosen randomly and the prize money is transferred to the winner's account.

This project is a guided project from Udemy.

# Prerequisites

To compile and deploy this smart contract, you will need the following:

- A Solidity compiler, such as Remix IDE
- An Ethereum wallet, such as MetaMask

# Getting Started

To get started, simply clone this repository to your local machine.

https://github.com/yourusername/lottery-smart-contract.git

# Usage

To use the contract, follow these steps:

- Compile the contract using a Solidity compiler
- Deploy the contract to the Ethereum blockchain
- Send Ether to the contract address to enter the lottery
- Wait for the winner to be chosen randomly
- If you are the winner, the prize money will be transferred to your account
- Contract Details

# Variables

manager - The address of the account that deployed the contract
players - An array of addresses representing the players who have entered the lottery

# Functions
enter - Allows players to enter the lottery by sending Ether to the contract address
random - Generates a random number based on the current block difficulty, timestamp, and player addresses
pickWinner - Chooses a winner randomly and transfers the prize money to their account
Getplayers - Returns the array of player addresses
