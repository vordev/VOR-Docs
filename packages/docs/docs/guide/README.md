# Introduction


VOR (Verified On-Chain Randomness) function  enables the generation of true (non-predictable) random numbers for interactions with smart contracts on the Ethereum network.

## How to Obtain Verified Onchain Documents for Dapps & Smart Contracts 

VOR is  
* 100% trustless
* decentralized
* Verifiable for producing random numbers. 
* Publicly queryable using the native token
* Provides ongoing rewards and incentives to participants

VOR is a fully open system, ready for use for any Dapps & ERC-20 Smart Contracts providing on-chain provably-fair and verifiable source of fair verified onchain randomness . Smart contract developers can use VOR as a reliable, rapidly deployable Random variable Generator to build trustless smart contracts for any applications which rely on unpredictable outcomes:

Unlike other VRF systems, VOR is fully open and ready to use by all with initial applications in gaming, NFTs, and distribution pools 

To get started in integration VOR”s function for your projects, follow the additional documentation below.


## On-chain Verification of Randomness

VOR utilizes a keyed cryptographic hash with private/public keys  that enables the holder of the private key to compute the hash while allowing  anyone with a public key hash to verify the proof & correctness of the hash to see how it was determined

The proof is published and verified on-chain before it can be used by any requesting Smart Contracts & Dapp which ensures that the results cannot be tampered with nor manipulated by anyone, including VOR’s node operators, miners, users and even smart contract developers.


## Obtaining a Verified On-Chain Random Variables

VOR  follows the Query & obtain data cycle. Utilizing two functions within the requesting contract 
1. requestRandomness, which makes the initial request for randomness.
2. fulfillRandomness, which is the function that receives and does something with verified randomness.
The contract will require a supply of the VOR token to vern the cost for the requests .
Request & Receive Data cycle. To consume randomness, your contract should inherit from VRFConsumerBase and define two required functions.

