# Random Number Game (using Chainlink VRF for randomness)
> WAGMI, Keep Buidling!

## LIVE AT: https://mumbai.polygonscan.com/address/0x35A8d1E76e505E0f4b7be227f19FF0222f443366



## About
When dealing with computers, randomness is an important but difficult issue to handle due to a computer's deterministic nature.
This is true even more so when speaking of blockchain because not only is the computer deterministic, but it is also transparent.
As a result, trusted random numbers cannot be generated natively in Solidity because randomness will be calculated
on-chain which is public info to all the miners and the users.

So we can use some web2 technologies to generate the randomness and then use them on-chain.

## Stack

React
Next.js

Vercel

Solidity (Hardhat)

IPFS (Pinata)

## Oracles

* An oracle sends data from the outside world to a blockchain's smart contract and vice-verca.
* Smart contract can then use this data to make a decision and change its state.
* They act as bridges between blockchains and the external world.
* However it is important to note that the blockchain oracle is not itself the data source
  but its job is to query, verify and authenticate the outside data and then futher pass it to the smart contract.

![logo](https://github.com/0xWick/chainlink-vrf/blob/19b0214f500e8dffa8a6f9e27b920c828058b7be/RandomWinnerGame/hardhat/0.png) =250x250)

Let's start building 🚀

## Basic Installation

## Intro:

Chainlink VRF's are oracles which used to generate random values.
These values are verified using cryptographic proofs.
These proofs prove that the results weren't tampered or manipulated by oracle operators, users, miners etc.
Proofs are published on-chain so that they can be verified.
After there verification is successful they are used by smart contracts which requested randomness.

## Usage example

Complete track for learning Web3 and make these amazing projects

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Follow the above link for complete setup!

<!-- Markdown link & img dfn's -->
[wiki]:  https://www.learnweb3.io/tracks/sophomore
