
# E-Voting System using Ethereum Blockchain (DAPP)
Build this e-voting decentralized application, or Dapp, on the Ethereum Network using these steps!

Follow the steps below to download, install, and run this project.

## Dependencies
These are the required prerequisites for this project, hence the host system must have these installed.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project or download the files
Link to clone project: `git clone https://github.com/aryan-mehta05/E-Voting-System-using-Ethereum-Blockchain`
After cloning/downloading the files, save them in your new project folder.

## Step 2. Install dependencies
```
$ cd <project-folder-name>
$ npm install
```

## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache. **!Remember this step while running the project since it may lead to errors and the project wont run!**

## Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

If you get stuck, please reference this video tutorial.
[DAPP University tutorial for Node, Truffle, Ganache and Metamask](https://www.youtube.com/watch?v=3681ZYbDSSk) `timestamp: 8:53 - 11:38`
