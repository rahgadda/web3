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
          - `RSA:`
            - It is a public-key encryption algorithm and the standard for encrypting data sent over the internet.
            - RSA is an asymmetric algorithm because it uses a pair of keys.
            - It uses public key to encrypt the message and a private key to decrypt it.

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
