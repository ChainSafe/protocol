---
layout: default
---

# ChainSafe Systems Technical Assessment

The following technical assessment is meant to give a first insight into your
capabilities as an engineer. The scope and the nature of the task do not reflect
future work at ChainSafe, but rather allow you to show off your open-source
skills on a reasonably compact project before applying to any of our open
positions.


### Simple Summary

It's as simple as that: You programmatically upload a file to the interplanetary
filesystem (IPFS) and store the resulting content identifier (CID) in a smart
contract deployed on any EVM-based blockchain.

### Requirements

Implement an open-source command-line tool that satisfies the following
requirements:

1. The command-line tool accepts a local file as an argument.
2. It uploads the file to the IPFS network
  - use an IPFS library to handle the upload
  - uploading the file should give you a CID for the next step
3. It stores the CID in a smart contract
  - you are free to use any EVM-based network, preferably an Ethereum
    testnet or a local environment (e.g., `ganache`)
  - the structure of the contract is not essential for this task as long as the
    CID is stored somehow

This exercise aims to understand better how you approach software development.
While we are concerned with the correctness of the implementation, we will also
be paying attention to the overall layout of the code and the contents of the
repository. Consider the necessary scripts, testing, and documentation for your
submission to be deemed a complete piece of well-engineered software.

### Resources

Deploying Smart Contracts:

- <https://ethereum.org/en/developers/docs/smart-contracts/deploying>
- <https://docs.openzeppelin.com/learn/deploying-and-interacting>

Running IPFS Nodes:

- <https://docs.ipfs.io/how-to/command-line-quick-start>

Using open-source libraries to ease the task is recommended and welcome.

### Further Instructions

All assignments must be submitted as a versioned repository. A commonly
used platform is GitHub.

- <https://github.com>

The task is designed to take not more than four hours. Incomplete
submissions will be accepted and reviewed to the best of our ability.
