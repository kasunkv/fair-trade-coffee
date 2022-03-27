# Fair Trade Coffee dApp - Udacity Blockchain Developer Nano-Degree Program
Fair Trade Coffee dApp is the supply chain project given as part of the Udacity Blockchain Developer Nano-Degree Program

## UML Diagrams
- [Activity Diagram](https://github.com/kasunkv/fair-trade-coffee/blob/master/uml-diagrams/fair-trade-coffee-activity-diagram.png)
- [Sequence Diagram](https://github.com/kasunkv/fair-trade-coffee/blob/master/uml-diagrams/fair-trade-coffee-sequence-diagram.png)
- [State Diagram](https://github.com/kasunkv/fair-trade-coffee/blob/master/uml-diagrams/fair-trade-coffee-state-diagram.png)
- [Class Diagram](https://github.com/kasunkv/fair-trade-coffee/blob/master/uml-diagrams/fair-trade-coffee-class-diagram.png)

## Libraries Used
- **Node v16.13.1**
- **Solidity v0.8.10**
- **Truffle v5.5.6**
- **Truffle Assertions v0.9.2** - _Used to easily assert events on the ethereum blockchain during unit testing_
- **Truffle HD Wallet Provider v1.0.17** - _HD wallet enabled Web3 provider used for deploying the contract on to the live networks_
- **Truffle Plugin Verify v0.5.24** - _Used to automatically verify the contracts on the live networks_
- **dotenv v16.0.0** - _Used to manage secrets as local environment variables_

## IPFS Usage
The web3 frontend is not deployed to the IPFS network

## Run Locally
1. On the project root run `npm install`
2. On the root directory and run `truffle develop` to run the local ganache blockchain
3. To compile the contracts run `compile`
4. To run the migrations run `migrate --reset`
5. To run the unit tests run `test`
6. To run the frontend, run `npm run serve` to run the webpack dev server.
7. Navigate to `http://localhost:3000` to see the application running.

## Contract Details - Rinkeby Network
- **Transaction Hash**: 0xec8157747e840737352b720271f43bfdfe402935fc323c5ddffaa7c2d97018b8
-  **Transaction Link**: [https://rinkeby.etherscan.io/tx/0xec8157747e840737352b720271f43bfdfe402935fc323c5ddffaa7c2d97018b8](https://rinkeby.etherscan.io/tx/0xec8157747e840737352b720271f43bfdfe402935fc323c5ddffaa7c2d97018b8)
-  **Contract Address**: 0x50bA6ba53E8a11Cc710173d3afe0c8dC1E50b257
-  **Etherscan URL**: [https://rinkeby.etherscan.io/address/0x50ba6ba53e8a11cc710173d3afe0c8dc1e50b257](https://rinkeby.etherscan.io/address/0x50ba6ba53e8a11cc710173d3afe0c8dc1e50b257)

## Screenshots
_Events - Deployed Contract on Rinkeby_
![Events - Deployed Contract on Rinkeby](https://raw.githubusercontent.com/kasunkv/fair-trade-coffee/master/screenshots/events-on-rinkeby-network.png)