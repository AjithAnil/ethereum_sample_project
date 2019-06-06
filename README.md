
# ethereum sample - Test project
This is a test project for ethereum


Follow the steps below to download, install, and run this project.

## Dependencies

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/AjithAnil/ethereum_sample.git`

## Step 2. Install dependencies
```
$ cd election_sample
$ npm install
```
## Step 3. Start Ganache
Download, install and open the Ganache GUI client. This will start the local blockchain instance.


## Step 4. Compile & Deploy Smart Contract
`$ truffle migrate --reset`
Migration is to be done for smart contract each time restart ganache.

## Step 5. Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000


