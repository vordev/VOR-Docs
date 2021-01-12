# Guide
This page explains how to get a random number inside a smart contract

## Random Number Consumer
To consume randomness, your contract should inherit from VRFConsumerBase and define two required functions.

* requestRandomness, which makes the initial request for randomness.
* fulfillRandomness, which is the function that receives and does something with verified randomness.

The contract should have enough funds (VOR) to pay the specified fee.

You can find the sample code to get a random number from github. (https://github.com/vordev/VOR-Contracts/blob/master/contracts/mock/RandomNumberConsumer.sol)
