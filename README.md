
# Housing Society E Voting - Ethereum based DAPP
Build decentralized application, or Dapp, on the Ethereum Network with this tutorial!

Video Tutorial:**
Here we can provide our Video link


Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/rahuyada46/BITS_BlockChainProject-main`

## Step 2. Move to the Project Directly on local computer 
Open Command prompt and then type
`$ cd BITS_BlockChainProject-main


## Step 2. Compile & Migrate smart contracts
`$ truffle compile 
This should result in Successful compilation (there may be certain warnings which can be ignored)
then `$ truffle migrate

## Step 3. Start Ganache
Open another command prompt move again to same project directory and type
`ganache-cli
this will start the ganache TestRPC on port 8454 for more details see https://docs.nethereum.com/en/latest/ethereum-and-clients/ganache-cli/


## Step 4. test the contracts 

 `$ truffle test 

 This should pass all 5 tests 

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000



