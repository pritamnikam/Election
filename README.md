# Election
A sample decentralized voting application using Smart Contract and Truffle.

# Step-by-step Guide
Install required tools:
1. Node and NPM
2. Truffle Framework
3. Ganache
4. Visual Studio Code and Solidity Extension
5. Metamask Chrome Extension.

1. Node.js and Node Package Manager (NPM)
$ node -v

2. Truffle Framework
It allows us to build decentralized applications on the Ethereum blockchain. It provides a suite of tools that allow us to write smart contacts with the Solidity programming language. It also enables us to test our smart contracts and deploy them to the blockchain. It also gives us a place to develop our client-side application.

$ npm install -g truffle

3. Ganache
The next dependency is Ganache, a local in-memory blockchain. You can install Ganache by downloading it from the Truffle Framework website.

4. Metamask
In order to use the blockchain, we must connect to it. We’ll have to install a special browser extension in order to use the Ethereum block chain.

5. Syntax Highlighting
Visual Studio Code


# Getting Started
1. let's create a project directory for our dApp 
$ mkdir election
$ cd election


2. To get up and running fast with a Truffle box. We'll be using the Pet Shop box for this tutorial.
$ truffle unbox pet-shop

3. Creating contracts
$ touch contracts/Election.sol

4. deploy it to the blockchain, we need to create a new file in the migrations directory.
$ touch migrations/2_deploy_contracts.js

5. let's run our migrations 
truffle migrate

6. Test the contracts
$ touch test/election.js
$ truffle test


7. Write the Client-Side Application and run the 
$ npm run dev



Setting the metamask
1. Once installed and login completes, make sure we setup the Ganache based localhost setup.
a. Go to Networks -> Custom RPC  -> Ge the Ganache port, eg. (http://localhost:7545).
b. Also make sure DApp connects to localhost localhost:
 Settings -> Connections  -> Add sites -> localhost

