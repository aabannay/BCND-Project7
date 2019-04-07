# Dates Supply Chain
This project is establishes a smart contract that resembles dates trade supplychain starting from the farmer all the way to the end consumer. The contract is divided into 3 main elements: 
1. ```Ownable.sol``` which controls the ownership of the contract and how it is transfered between multiple addresses i.e. accounts. 
2. ```access control``` which controls the access and different roles of actors on the supplychain this includes the following: 
2.1. ```Farmer.sol```
2.2. ```Distributor.sol```
2.3. ```Retailer.sol```
2.4. ```Consumer.sol```
3.```supplychain.sol``` which controls the interactions with the supplychain allowing farmer to harvest, process, pack and sell dates. Allowing distirbutor to buy and ship dates. Allowing retailers to recieve the shipment and allowing the consumer to purchase from retailers. 

In addition, there is a from end resebled by ```index.html``` which used ```app.js``` and ```truffle-contract.js```. 

Finally, testing is covered under the folder test using ```TestSupplychain.js```.

## UML Diagrams
UML diagrams can be found on the [UML](uml) folder. 
The diagrams included are:
1. activity, 
2. sequence, 
3. state, and 
4. data model diagrams. 

## Contract Publishing 
The contract is published already on rinkeby network on Ethereum blockchain with the following transaction address: 
```
0x99dffba480787d5d3932d3f06953dbf6b10f6c5286997c5f2d3af9caedae484d
```
and the following contract address: 
```
0x4d791cB191F2aDC1c00DAaAD0D7553e9ed13613B
```
Full migration code can be found on [migration.txt](migration.txt).
## How to use
The original code used for this project was clone as follows: 
```git clone https://github.com/udacity/nd1309-Project-6b-Example-Template.git```

To have the working complete code clone this repo and do the following: 
1. Once installed, go into your cloned directory, and run ```npm install```
2. For starting the development console, run ```truffle develop```
3. For compiling the contract, inside the development console, run ```compile```
4. For running unit tests the contract, inside the development console, run ```test``` or run ```truffle test``` outside the development environment of truffle. 
5. For migrating the contract to the locally running ethereum network, inside the development console, run ```migrate --reset```
6. For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run ```npm run dev```

## Tools
In order to be able to operate the contract you would need the following tools: 
1. Ganache (GUI tool or ganache-cli)
2. MetaMask (browser plug-in)
3. node
4. npm
5. development environment.