Simple demonstration to query deployed ethereum contracts quickly using web3.

This could have been done without truffle but using truffle makes life easier.

## Pre-requisites

* Install [truffle](https://github.com/trufflesuite/truffle), [metamask](https://metamask.io/) (Optional)

* Signed up with [infura.io] and have the api keys.

## Installation

* clone this repo

* cd repo, `npm install`

* `cp .env.sample .env` and update values 

## Execution

In query.js

* Update contract_address.

* update abi. abi can be copied directly from the contract source in etherscan.io 

* Update query logic function

Once ready, `truffle exec query.js --network main`

