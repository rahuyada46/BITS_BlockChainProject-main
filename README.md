# Housing Society E Voting - Ethereum based DAPP
Build decentralized application, or Dapp, on the Ethereum Network with this tutorial!

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. 
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/rahuyada46/BITS_BlockChainProject-main` note: Repository is private and for Assignment purpose the code is provided as part of Zip File

## Step 2. Move to the Project Directly on local computer 
Open Command prompt and then type
`$ cd BITS_BlockChainProject-main


## Step 2. Compile & Migrate smart contracts
in the command prompt type
`$ truffle compile 
This should result in Successful compilation (there may be certain warnings which can be ignored)

## Step 3. Start Ganache
Open another command prompt move again to same project directory and type
`ganache-cli
this will start the ganache TestRPC on port 8454 for more details see https://docs.nethereum.com/en/latest/ethereum-and-clients/ganache-cli/


## Step 4. Migrate and test the contracts 
go back to first command prompt where truffle compile command was used now use below commands one after another
 `$ truffle migrate - it should deploy the contracts on the Development network
 then
 `$ truffle test 

 This should pass all 5 tests 

## Step 5. Configure Metamask
Metamask can be added as the browser extension - for this project Chrome brower is used
- Configure Metamask as new wallett
- Unlock Metamask 
- Connect metamask to your local Etherum blockchain provided by Ganache localhost 8545.
- Import an account provided by ganache using the Private Keys

If Metamask is showing not connected please use below steps

Step 1. Click right corner dotted button for selected account.
Step 2. Click on Connected sites.
Step 3. Click Manually connect to current site.
Step 4. Select your account and click next button.
Step 5. Next Screen for confirmation click Connect button and It will show new screen connected and now it will show connected 



## Step 6. Run the Front End Application
Open a new command prompt go to Project Directory and then type
`$ npm run dev`

-If this command is causing problem in Mac OS or Windows like permission issues or lite server is not a recognized command then we can try installing 

   $npm install lite-server -g
and then again try    `$ npm run dev`
as soon as this command is executed the brower will load the E-Voting Application page

This URL will open in your browser: http://localhost:3000 with application showing a message "Voting begins "please connect your Account to Metamask..."
