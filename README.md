# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

> The starter code is written for **Solidity v0.4.24**. At the time of writing, the current Truffle v5 comes with Solidity v0.5 that requires function *mutability* and *visibility* to be specified (please refer to Solidity [documentation](https://docs.soliditylang.org/en/v0.5.0/050-breaking-changes.html) for more details). To use this starter code, please run `npm i -g truffle@4.1.14` to install Truffle v4 with Solidity v0.4.24. 

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "legend road trial smooth neck access asthma scale typical retreat unique gadget"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS

# Student Comments

## Requirement 1: UML Diagrams

### Activity Diagram
![truffle test](/images/ActivityDiagram.png)

### Sequence Diagram
![truffle test](/images/SequenceDiagram.png)
### State Diagram
![truffle test](images/StateDiagram.png)
### Data Model Diagram 
![truffle test](/images/DataModel.png)

## Requirement 2: Libraries used
- Truffle: Deployment and testing
- Solidity: Programming language for smart contracts
- OpenZeppelin: minimizes risk by using battle-tested libraries of smart contracts
- Node: Deployment UI to the browser
- Web3.js: Interaction with Ehtereum node

### Version
Truffle v4.1.14 (core: 4.1.14)
Solidity v0.4.24 (solc-js)
Node v16.11.1
Web3.js v1.5.3

## Requirement 3: General Info

### Accounts used
Contract: 0xee32c3913378D55a8f7D88B3f335D9aec084E258(https://rinkeby.etherscan.io/address/0xee32c3913378d55a8f7d88b3f335d9aec084e258)
Contract Owner: accounts[0]  0xc2ed033dd19b358c935ed7c3df3b9297ae78ddbe
Farmer: accounts[1]  0x8b86950eb6f858fa6e21ea65b535ef888355b831
Distributor: accounts[2]  0xf29176e6ed03c180fad4fc37f6b35cfbeabbb4b7
Retailer: accounts[3]  0xe53bf2bb4e66f9c5c1b436151681a9734123dd25
Consumer: accounts[4]  0x16212930a1062b89b56ee65a719053ed61d2ef37

### IPFS
IPFS was not used in this project

# SupplyChain_Proj3
