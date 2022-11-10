# BlockchainExpert - ERC20 and DEX Contract

This project provides two smart contracts, one that implements a ERC20 token and another that allows users to sell/transfer their tokens. This project includes automated testing and a slim frontend for interacting with these contracts.

## Getting Started

To test and deploy the smart contract follow the steps below.

1. Install [Node.js](https://nodejs.org/en/download/)
2. Clone the repository: `git clone https://github.com/algoexpert-io/ERC20-DEX.git`
3. `cd ERC20-DEX`
4. `npm install`
5. To test the contract run `npx hardhat test`
6. To deploy the contract to your `localhost` network do the following:
   - `npx hardhat node`
   - `npx hardhat run --network localhost ./script/deploy.js`

## Using the Frontend

1. Install the [Liveserver Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VSCode.
2. Open [base.html](frontend/base.html)
3. Click the button that says "Go Live" in the bottom right hand corner of your VSCode.
4. Import any accounts you need into MetaMask and change your MetaMask network to "Hardhat".
5. Interact with the contract!
