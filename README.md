# Web3

## Table of Content
1. [Overview](#overview)
2. [History](#history)
3. [Modules](#modules)
4. [Glossary](#glossary)
5. [References](#references)

## Overview
- To learn Blockchain or Web3, we need below tool kits
  - **Framework:**
    - `Solana:` It is a public hosted platform.
    - `Ethereum`: It is a public hosted platform.
    - `Hyperledger:` It is an open-source platform that allows to creation of company internal blockchains.
    - `Celestia:`
  - **Programming Language:**
    - `Rust:` This is the base programming language on which Web3 Framework can interact. 
    - `Chaincode:` This is used by Hyperledger.
    - `Solidity:` Ethereum uses this.

## History
- The world of `Blockchain` started with a crypto currency `Bitcoin`.
  - It works on below foundation principles:
    - **Cryptography:** 
      - It is the process of hiding or coding information so that only the person a message was intended for can read it.
      - Different encryption algorithms are used to convert plain text into cypher text. These techniques are called encryption and decryption.
      ![](./01-images/Encryption-Decryption.png)
      - There are different types of Cryptography encryption techniques: Symmetric, Asymmetric and Hashing.
        - Symmetric encryption uses same keys to encrypt and decrypt. Asymmetric encryption uses public and private keys to to encrypt and decrypt.
        ![](./01-images/Asymmetric-vs-Symmetric.png)
      - It has below building blocks:
        - `Public & Private Key:`
          - `Public Key:` 
            - This is shared with everyone. 
          - `Private Key:`
            - This is not shared with everyone and is kept as a secret.
          - `Confidentiality:`
            - Client/Sender will encrypt data that he wanted to send using the public key available.
            - This will allow only Server/Consumer with valid private key only to read the data and ensure the data packets are not tampered.  
          - `Signature:`
            - Server/Consumer will encrypt data that he wanted to send using his secret private key.
            - This can be decrpted using public key available ensuring the data is received only from Server/Consumer and not tampered.

          ![](./01-images/HowInternetWorks.png)
        - `Algorithm:`
          - Algorithms are the rules or instructions for the encryption process. 
          - The key length, functionality, and features of the encryption system in use determine the effectiveness of the encryption. Typically length of keys range from 128 to 256 bits.
          - An encryption key is a randomized string of bits used to encrypt and decrypt data. The longer keys are harder to break.
          - `RSA - Rivest Shamir Adleman:`
            - It is a public-key encryption algorithm and the standard for encrypting data sent over the internet.
            - RSA is an asymmetric algorithm because it uses a pair of keys.
            - It uses public key to encrypt the message and a private key to decrypt it.
            - It is widely used in securing data transmission, authentication, and digital signatures. It's particularly efficient for securing communications over the internet.
            - HTTPS - SSL uses RSA.
          - `SHA - Secure Hashing Algorithm:`
            - It is the common name for a family of cryptographic hash functions.
            - It is used to generate a fixed-size hash value (digest) from input data of variable length.
            - Bitcoin usese SHA-256.
    - **Distributed Ledger:**
      - Ledger refer to book keeping of all the transactions that take place in an organization or a business unit.
      - Traditionally banks or online platforms use databases to store this data to indicate movements of resources like money, goods etc.. between registered parties. These are prone to hacking and un-authorized transactions creating trustless eco-system.
      - To solve this problem a free market ideology called `Bitcoin` was invented in `2008 by Satoshi Nakamoto`, an unknown person. Use of bitcoin as a currency `began in 2009`, with the release of its `open-source implementation`.
        - `Nodes:` These are computation building blocks that create peer-to-peer network to verify transactions through cryptography and record them in a public distributed ledger.
        - `Mining:` Consensus between nodes on final list of transactions is achieved using a computationally intensive system based on proof-of-work.
        - `Block:` 
          - It is contain information of transacation like names, places, times, cost,previous block hash, current block hash, markle tree and block ID, etc or any other type of data. 
          - These blocks cannot be deleted or updated once created.
        - `Blockchain:`
          - Individual blocks are cryptographically verified and chained up to form an immutable chain called a blockchain.
          - The same chain is then distributed to all the nodes across the network via a P2P network.
          - Instead of a centralized database, all the transactions (data) that are shared across the nodes are contained in blocks, which are chained together to create the ledger.
          - All the data in the ledger is secured by cryptographic hashing and digital signature and validated by a consensus algorithm. 
          - Nodes on the network participate to ensure that all copies of the data distributed across the network are the same.

        ![](./01-images/blockchain.jpeg)
        ![](./01-images/blockchain-node.jpeg)
        ![](./01-images/ConsensusAlgo.png)

## Modules

## Glossary
- **DeFi:** Decentalized Finance
- **DAO's:** Decentalized Autonomus Organizations
- **DApp:** Decentalized Application
- **NFT:** Non Fudgable Tokens
- **Blockchain:** It is a collaboration-enabling technology that replace `brand-based trust` with `math-based trust` by shifting the hosting, execution, enforcement, and custody mechanisms of a contract to software logic run across a decentralized network that no individual participant can undermine. `Trust Minimized Agrements`
- **Blockchain Oracle:** These are entities that connect blockchains to external systems, thereby enabling smart contracts to execute based upon inputs and outputs from the real world. More details available [here](https://chain.link/education/blockchain-oracles#types-of-blockchain-oracles)
- **Hybrid Smart Contracts:** It combines code running on the blockchain (on-chain) with data and computation from outside the blockchain (off-chain) provided by decentralized oracle networks.

## References
- [Why Solana](https://www.investopedia.com/solana-5210472)
- [Harkirat Singh - Inspiration](https://www.youtube.com/watch?v=ERAxd8gl1Eg&list=PLVKLWop9wWA9n9NQZ2GURoB_a1gOezN_e&index=3)
- [DApp University - Inspiration](https://www.youtube.com/watch?v=VH9Q2lf2mNo)
- [Hyperledger](https://www.hyperledger.org/)
- [Freecodecamp - Learn Blockchain](https://www.youtube.com/watch?v=gyMwXuJrbJQ)
- [Local Blockchain - Truffle Ganache](https://trufflesuite.com/ganache/)
- [Connect to Blockchain - Metamask](https://metamask.io/)
