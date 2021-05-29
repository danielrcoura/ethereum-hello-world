# Ethereum Hello World
Simple Smart Contract

https://medium.com/compound-finance/setting-up-an-ethereum-development-environment-7c387664c5fe#:~:text=Ethereum%20Networks%20%2D%20The%20Ethereum%20Main,be%20accessed%20via%20Infura's%20API.

## Install
npm i

## Build the smart contract
npx solcjs --bin --abi -o ./build FirstContract.sol

## Deploy the smart contract to Ganache CLI
npx ganache-cli
node deploy.js

## Run the frontend
npx http-server


