# Arbitrum Sepolia Testnet Smart Contract Deployment

In this project, I demonstrate the process of setting up a development environment on the Arbitrum Sepolia Testnet and deploying a simple smart contract. 
This includes steps for configuring MetaMask, acquiring testnet ETH, writing a smart contract, compiling it, deploying to the Arbitrum Sepolia network, and interacting with it.

## Steps to Set Up the Arbitrum Sepolia Environment

1. **MetaMask Configuration**: I started by configuring MetaMask to connect with the Arbitrum Sepolia Testnet.
   This involved adding network details in MetaMask (RPC URL, Chain ID, etc.) to enable transactions on the Arbitrum test network.
3. **Acquiring Testnet ETH**: To fund test transactions, I bridged existing Sepolia ETH from Ethereum Sepolia to Arbitrum Sepolia using the Arbitrum Bridge.
   This allowed me to transfer Sepolia test ETH from Ethereum Sepolia directly to the Arbitrum Sepolia test network.

## Writing, Compiling, and Deploying the Smart Contract

1. **Writing the Contract**: Using Remix IDE, I created a new file named `HelloArbitrum.sol`. This contract includes a `message` state variable,
   a constructor for setting an initial message, and a function to update the message.
3. **Compiling the Contract**: I compiled the contract using Remix’s Solidity Compiler, ensuring compatibility with Solidity version `^0.8.25`.
   Any errors in the code were resolved before deployment.
5. **Deploying to Arbitrum Sepolia**: After connecting Remix to MetaMask, I selected the Arbitrum Sepolia network and deployed the contract,
   confirming the transaction in MetaMask. I then verified the deployed contract’s address on the Arbitrum Sepolia Explorer (Arbiscan).

## Interacting with the Contract

With the contract deployed, I used Remix to interact with it. I accessed the initial `message` value using the `message()` function, 
and then updated the message with the `updateMessage` function to verify the contract's functionality.
