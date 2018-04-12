Simple demonstration to query deployed ethereum contracts quickly using web3.

This could have been done without truffle but using truffle makes life easier.

## Pre-requisites

* Install [truffle](https://github.com/trufflesuite/truffle)

* Signed up with [infura.io] and have the api keys.

## Installation

* clone this repo

* cd repo, `npm install`

* `cp .env.sample .env` and update values 

* If you want to make queries that require ether, you will need to create an ethereum account from a HD wallet. [metamask](https://metamask.io/) could be a quick an easy option. Install metamask and get the mnemonic key. Then update .env with the key.

## Execution

In query.js

* Update contract_address.

* update abi. abi can be copied directly from the contract source in etherscan.io 

* Update query logic function

Once ready, `truffle exec query.js --network main`
