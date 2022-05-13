# Hello World

HelloWorld is a simple blockchain application written in JavaScript and Solidity. It provides very basic functionality like writing data to the blockchain network and reading that data from the same network. Ropsten Testnet is used in this project to make it work.

## Setup

You can clone this repository.
```bash
git clone 
cd Hello-world/
```

Quick Start
-
- run this command to set up all the dependencies (hardhat, ethers, etc.)
```bash
npm install
```
- set up an Alchemy account [here](https://www.alchemy.com/)
- set up a [MetaMask](https://metamask.io/download.html) wallet with [fake testnet ether](https://faucet.dimensions.network/)
- here I've used [Ropsten testnet](https://ropsten.etherscan.io/).
- transfer fake ethereum to the Metamask wallet using [link1](https://faucet.dimensions.network/) or [link2](https://faucet.egorfine.com/).
- create a file named '.env' and store all the information as shown below.
```bash
API_URL=https://eth-ropsten.alchemyapi.io/v2/12345
API_KEY=12345
CONTRACT_ADDRESS=0x0cD6CbFa307AEcCF7BEd7f3583fBd29e9D52F1Bc
PRIVATE_KEY=1234567890
```



## Deploying Commands
- run this command to deploy the contract to the Ropsten testnet.

```bash
npx hardhat run scripts/deploy.js
```
- run this command to read and write a new message to the smart contract on Ropsten testnet.
```bash
npx hardhat run scripts/interact.js
```

## References
- [Node.js](https://nodejs.org/en/)
- [MetaMask](https://metamask.io/)
- [etherscan](https://ropsten.etherscan.io/)
- [Hardhat](https://hardhat.org/)
- [Alchemy](https://www.alchemy.com/)

