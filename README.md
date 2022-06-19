# evm-cli

an evm cli which supports any evm chain

# interface

## config

- config:network:list
- config:network:add [network] [rpc-url] [etherscan-api-key]
- config:network:remove [network]
- config:network:default [network]
- config:signer:add [privateKey]

## address

- address:add [address]
- address:remove [address]
- address:list
- address:balance [address]
- address:transactions [address] --watch

## wallet

- wallet:create

## abi

- abi:cat [address] [--mainnet] [--events/methods/all]

## block

- block:get [blockHash/blockNumber][network]
- block:get:number [blockHash/blockNumber][network]
- block:get:uncle [blockHash/blockNumber][network]
- block:number [network] [--watch]

## contract

### events

### methods

## trasactions

- pending transactions

## code

## utils

## typings

## ens

## big number

## hashing

## uniswap

## ipfs

## gas

## prices

## multicall
