# Software Checkpoint - Modification of the Election DAPP Tutorial
This is a learning project and implementation of the Election DAPP Tutorial.

This project has been made as part of the course APS1050 Blockchain and Cryptocurrencies at the University of Toronto, 2021.

The interface, some packages and functions were improved for the specific scenario of a checkpoint for the users who may choose their preferred Licence Option before starting to use a commercial solution.

Election DAPP Tutorial follows.

Full Free Video Tutorial:**
https://youtu.be/3681ZYbDSSk

## 2019 Updated Code
https://github.com/dappuniversity/election/tree/2019_update

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/dappuniversity/election`

## Step 2. Install dependencies
```
$ cd election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

If you get stuck, please reference the free video tutorial.

