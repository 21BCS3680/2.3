# Message Storage Smart Contract and Web Frontend

This repository contains a simple Solidity smart contract for storing and retrieving a message, along with a basic web frontend to interact with the contract.

## Prerequisites

Before getting started, ensure you have the following prerequisites installed:

- Ethereum development environment (e.g., Ganache)
- Ethereum wallet in your browser (e.g., MetaMask)

## Smart Contract

1. Create a new Solidity file (e.g., `MessageStorage.sol`) and paste the smart contract code into it.

2. Compile and deploy the smart contract using a development framework like Truffle or an online development environment like Remix.

3. After deployment, note the contract address and ABI (Application Binary Interface).

## Web Frontend

1. Create an HTML file (e.g., `index.html`) and paste the HTML and JavaScript code provided in the repository.

2. Replace `'YOUR_CONTRACT_ADDRESS'` in the JavaScript code with the actual contract address obtained during deployment.

3. Ensure that the ABI in the frontend code matches the ABI of your deployed contract.

## Usage

1. Serve the HTML page using a local development server or a tool like Live Server (if using Visual Studio Code).

2. Open the HTML page in your web browser.

3. Connect MetaMask to your local development blockchain or testnet.

4. Use the "Set Message" button to set a new message.

5. Use the "Get Message" button to retrieve and display the current message on the web page.

## Note

- This is a simplified example for demonstration purposes. In a production environment, you would typically deploy your contract to the Ethereum mainnet, handle more complex functionality, and ensure proper security practices.

- Ensure the security of your private keys and manage your Ethereum wallet safely.

