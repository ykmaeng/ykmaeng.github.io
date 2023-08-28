---
title: "Cosmos: Tendermint"
subtitle: ""
date: 2023-08-28T22:19:02+12:00
tags: ["blockchain", "cosmos", "tendermint"]
categories: ["projects", "tint"]
author: "Young"
authorLink: ""

toc: false
lightgallery: true

draft: true
---

Tendermint is an open-source software that packages the networking and consensus layers of a blockchain into a generic engine, allowing developers to build their application-specific blockchains. It's a fundamental part of the Cosmos Network.

Tendermint consists of two main technical components:

1. **Tendermint Core**: This is the software implementation of a Byzantine Fault Tolerant (BFT) consensus algorithm. In simpler terms, it's a protocol that ensures all nodes in the network agree on the state of a distributed ledger, even if some nodes fail or act maliciously. It provides high transaction speed, scalability, and security.

2. **Application Blockchain Interface (ABCI)**: This is the interface that connects the Tendermint Core and the blockchain application. ABCI allows the blockchain transaction processing part, also known as the application layer, to be built in any programming language, which opens up enormous possibilities for developers.

Tendermint uses a round-robin process to propose new blocks, which means that each validator in the network gets a chance to propose a block. This is different from other consensus algorithms like Proof-of-Work (used by Bitcoin) and Proof-of-Stake (used by Ethereum 2.0), where the right to propose a block is based on computational power or the amount of stake, respectively.

One of the key features of Tendermint is instant finality. This means that forks are extremely rare, and transactions don't require multiple confirmations, contrasting with blockchains like Bitcoin where transactions are only probabilistically final.

Overall, Tendermint provides a robust and secure backbone for building custom blockchains, making it a popular choice among blockchain developers.