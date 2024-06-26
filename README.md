# Ethereum ATM Contract

## Overview

This project showcases a decentralized application (DApp) built on the Ethereum blockchain using Solidity for smart contracts and React.js for the frontend. The DApp enables users to connect their MetaMask wallet, interact with a counter smart contract on Ethereum test networks, view contract details, deposit funds, and withdraw funds.

## Smart Contract Capabilities

The deployed smart contract for this DApp includes the following functions:

- **getBalance**: Returns the current balance of the smart contract.
- **deposit**: Allows users to deposit ETH into the smart contract.
- **withdraw**: Allows the owner to withdraw ETH from the smart contract.
- **viewDetails**: Provides the owner's address and the current balance of the smart contract.

## Frontend Functionality

### Setup Instructions

To get the code running on your computer after cloning the GitHub repository, follow these steps:

1. Navigate to the project directory and install dependencies:

   ```bash
   npm install
   ```
   
2. Open two additional terminals in your VS code.

3. In the second terminal, start the Hardhat development network:

```bash
npx hardhat node
```

4. In the third terminal, deploy the smart contract to the local network:

```bash
   npx hardhat run --network localhost scripts/deploy.js
```

5. Back in the first terminal, start the frontend development server:

```bash
   npm run dev
```

6. Open your browser and navigate to http://localhost:3000 to view the application.

## Using the DApp
To interact with the Ethereum Counter DApp:

* Connect your MetaMask wallet to the DApp.
* View the current contract balance stored in the smart contract.
* Deposit funds by clicking the "Deposit" button.
* Withdraw funds by clicking the "Withdraw" button (only available to the owner).
* View contract details by clicking the "View Contract Details" button.

## Assistance 
For common issues or troubleshooting, please refer to the README.md file.

## Author
Allen Kyle Sabilala  
[@Kycehhh](https://twitter.com/Kycehhh)

## License
This project is licensed under the MIT License. See the LICENSE.md file for more details.
