# Augurs Private Network Chain Explorer

This Etherchain instance is pointed at the Augur private chain currently powering the Augur app. Etherchain only supports Parity at the moment, while Augurs nodes are running Geth. Due to this, only the main page showing blocks and transactions will work. When we get an Augur node running on Parity, this explorer will have full functionality. 

## Getting started

Supported OS: Ubuntu 16.04

Supported Ethereum backend nodes: Parity

1. Clone this repository to your local machine: `git clone https://github.com/gobitfly/etherchain-light --recursive` (Make sure to include `--recursive` in order to fetch the solc-bin git submodule)
2. Install all dependencies: `npm install`
3. Adjust the `config.js` file to your local environment
4. Start the explorer: `npm start`
5. Browse to `http://localhost:3000`

## Current Features
* Browse blocks, transactions, accounts and contracts
* View pending transactions
* Display contract internal calls (call, create, suicide)
* Upload & verify contract sources
* Named accounts
* Advanced transaction tracing (VM Traces & State Diff)
* View failed transactions
* Live Backend Node status display
* Submit signed Transactions to the Network
* Support for all [Bootswatch](https://bootswatch.com/) skins
* Accounts enumeration

## Planned features
* ERC20 Token support
* Signature verification
* Load balanced HTTP JSON-RPC backend support
* Contract state evaluation
