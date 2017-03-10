# Augurs Private Network Chain Explorer

This Etherchain instance is pointed at the Augur private chain currently powering the Augur app. Etherchain only supports Parity at the moment, while Augurs nodes are running Geth. Due to this, only the main page showing blocks and transactions will work. When we get an Augur node running on Parity, this explorer will have full functionality. 

## Getting started

1. Clone this repository to your local machine: `git clone https://github.com/gobitfly/etherchain-light --recursive` (Make sure to include `--recursive` in order to fetch the solc-bin git submodule)
2. Install all dependencies: `npm install`
3. Adjust the `config.js` file to your local environment
4. Start the explorer: `npm start`
5. Browse to `http://localhost:3000`
